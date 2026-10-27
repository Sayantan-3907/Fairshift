# FairShift – Decent Work Platform (SDG 8)

> **Theme:** SDG 8 – Decent Work and Economic Growth  
> **Target Audience:** Employee-intensive organizations (Construction Sites, Educational Institutions)

---

## 🌟 Architectural Features & Device Compatibility

FairShift is built with a **Universal Client Architecture** designed for maximum offline capability, low-end device compatibility, and containerized cloud scalability.

- **Cross-Platform Compatibility:** Runs seamlessly on laptops, desktop browsers, and budget Android smartphones without requiring a local backend runtime.
- **Offline-First & Zero-Database Architecture:** Utilizes reactive browser state (`localStorage`) pre-seeded with multi-industry operational data.
- **Containerized Serverless Deployment:** Includes production-ready `Dockerfile` and `nginx.conf` listening on port `8080` for instant deployment to Google Cloud Run.
- **Enterprise Security Hardening:** Features client-side XSS input sanitization, SHA-256 client metadata stripping for anonymous safety reporting, and role-based access control (RBAC).

---

## 🚀 How to Run Locally

Clone the repository and open `index.html` directly in any web browser:

```bash
git clone [https://github.com/Sayantan-3907/Fairshift.git](https://github.com/Sayantan-3907/Fairshift.git)
cd fairshift
# Open index.html in your browser