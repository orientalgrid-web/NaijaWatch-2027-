# NaijaWatch 2027 — Citizen Collation & Verification Portal

**Property of:** Apps & Algorithm Concept  
**Contact Email:** `dev@connectorient.com.ng`  
**Attention:** Douglas Idima  

## Overview

NaijaWatch 2027 is a single-file, offline-capable HTML/CSS/JavaScript web portal designed for citizen election monitoring, polling unit result sheet verification, incident reporting, cloud vault backup/recall, and live multi-user coordination via **The Situation Room** (with **Desktop Mode**).

### Key Features Included
- **Instant Biometric Camera Lock:** Prompts for a **Face Photograph** and **Camera-Lens Bio Thumbprint** scan after selecting a status/role.
- **All 22 INEC-Registered Political Parties & Symbols:** Includes `A`, `AA`, `AAC`, `ADC`, `ADP`, `APC`, `APGA`, `APM`, `APP`, `BP`, `DLA`, `LP`, `NDC` (with two-finger "V" symbol), `NDP`, `NNPP`, `NRM`, `PDP`, `PRP`, `SDP`, `YP`, `YPP`, and `ZLP`.
- **10-Meter Geofence & 5-Upload / 3-of-5 Consensus Engine:** Enforces 10m polling unit proximity checks, a 5-submission cap per polling unit, and automatic **3-of-5 majority consensus** verification.
- **Official Visual Proof:** Captures and stamps photos of the **Result Sheet**, **Presiding Officer holding the signed result sheet**, and **Ad-Hoc Staff**, alongside the uploader's verified face photograph.
- **Incident Reporting & Cloud Vault:** Supports photo and video incident reports, AI classification assist, offline queue sync, and Cloud Save & Recall.
- **The Situation Room & Desktop Mode:** Built-in Zoom / Google Meet / Microsoft Teams / Jitsi Meet room hub with a toggleable **Desktop Mode** docked monitoring rail.

## How to Upload to Your Computer & Push to GitHub

1. Download or save `index.html` (and `README.md`) into a folder on your computer, for example `naijawatch-2027/`.
2. Open a terminal inside `naijawatch-2027/` and run:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit: NaijaWatch 2027 portal"
   git branch -M main
   git remote add origin https://github.com/<your-username>/naijawatch-2027.git
   git push -u origin main
   ```
3. To host live on **GitHub Pages**, go to your repository on GitHub -> **Settings** -> **Pages**, select **Deploy from a branch** (`main` / `/ (root)`), and save. (HTTPS is required by browsers for live camera and geolocation access.)
