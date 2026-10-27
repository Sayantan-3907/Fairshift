# FairShift — SDG 8 Decent Work & Safety Vault

FairShift is an enterprise operations platform designed to align field operations with **UN SDG 8 (Decent Work and Economic Growth)**. It integrates real-time ILO fatigue risk calculations, transparent automated wage breakdown, and client-side cryptographic anonymous grievance vaults.

## Key Modules & Technical Features

### 1. ⏱️ Real-Time Shift & Telemetry Engine (ILO Standard)
* Calculates real-time fatigue index based on continuous hours worked ($T_{continuous}$) and ambient site temperature ($Temp_{ambient}$).
* Triggers automated visual and ARIA-announced safety breach warnings when continuous shift duration exceeds 4 hours without rest.

### 2. 💰 Transparent SDG 8 Wage & Audit Engine
* Calculates base wages, statutory welfare fund deductions (5%), and mandatory 1.5x overtime premiums.
* Supports client-side cryptographic payslip generation formatted for PDF exports.

### 3. 🔐 Anonymous Grievance Vault (SHA-256)
* Strips all device metadata, browser fingerprints, and IP context client-side.
* Generates cryptographically anchored tokens (`FS-2026-XXXX`) using `Crypto.subtle.digest('SHA-256')`.

## Security & Accessibility Standards
* **Security:** Complete client-side HTML input sanitization against XSS/script injection.
* **Accessibility (a11y):** Full ARIA labels, `aria-live` dynamic region announcements, semantic HTML5 sectioning (`<main>`, `<header>`, `<nav>`), and high-contrast WCAG 2.1 AAA compliant UI palette.
* **Testing:** Standardized automated test suite (`test.js`).

## How to Run
Open `index.html` in any web browser or run `npm test` to execute the automated verification suite.