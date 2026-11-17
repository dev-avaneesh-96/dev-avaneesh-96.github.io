# dev-avaneesh-96.github.io

Personal CV / Portfolio website hosted on GitHub Pages at [https://dev-avaneesh-96.github.io/](https://dev-avaneesh-96.github.io/).

## Versions Included

- **`index.html` (Version 2.0 - Active / Default):**
  - Updated specifically for **Native & Cross-Platform Mobile App Developer** roles (10 Years Experience).
  - Removed "Open to full-time opportunities" badge from the header as requested.
  - Retained the **AI-assisted, MCP-driven workflow** section.
  - Tailored **What I build** section for mobile: Cross-Platform (React Native, Flutter), Native iOS (Swift, Objective-C), Hardware & IoT (BLE printer discovery, NFC, Barcode & QR smart scanning), Enterprise Architecture (SSO), and E-Commerce/UX (Order management, Haptic Bot, Cashback/Coupons).
  - Added comprehensive **Professional Experience** section covering:
    - **Tata Consultancy Services** (Iron Mountain Information Management, LLC) — React Native Developer
    - **Dew Solutions Pvt Ltd** — iOS Developer
    - **Pepal Private Limited** — iOS Developer
    - **Shine Web Solutions Pvt Ltd** — iOS Developer
  - Refreshed **Skills & Tech Stack** chips, added TCS **Awards & Honors**, **Certifications**, and **Education**.
  - Built-in navigation toggle to access the archived version.

- **`v1.html` (Version 1.0 - Archived Original):**
  - Complete, preserved copy of the original CV (Full-Stack & Web developer focus).
  - Includes toggle link back to the updated CV.

## Deployment to GitHub Pages

To publish this new version to your live site:

```bash
# 1. Initialize or navigate to your git repo
cd /Users/avaneesh/.gemini/antigravity/scratch/dev-avaneesh-96.github.io

# If not already connected to GitHub:
git init
git remote add origin https://github.com/dev-avaneesh-96/dev-avaneesh-96.github.io.git

# 2. Stage and commit both versions
git add index.html v1.html README.md
git commit -m "Update CV to Mobile App Developer v2.0 and archive v1"

# 3. Push to GitHub (main branch)
git branch -M main
git push -u origin main
```
