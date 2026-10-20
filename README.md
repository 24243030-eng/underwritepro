# UnderwritePro — Insurance Risk Desk

A responsive frontend-only underwriting management system built for the Data Alcott Systems task WD-INS-005.

## Features
- Dashboard with live application counts and risk distribution
- Application creation, search and filtering
- Illustrative risk calculator
- Underwriting guideline cards
- Decision management (approve, decline, request more info, refer to senior, counter offer)
- Simulated policy issuance for approved applications
- Document register (file metadata only; actual file contents are not uploaded or stored)
- Reports and CSV export
- Dark mode and responsive mobile navigation
- Local browser storage for demo records

## Technologies
HTML5, CSS3, vanilla JavaScript, localStorage. No database, build tools or API keys required.

## Run locally
1. Extract `UnderwritePro.zip`.
2. Open the `UnderwritePro` folder.
3. Double-click `index.html` to open it in Chrome, Firefox or Edge.

If your browser restricts some local-file behavior, use VS Code with the **Live Server** extension:
1. Open the folder in VS Code.
2. Right-click `index.html`.
3. Choose **Open with Live Server**.

## Publish using GitHub Pages
1. Create a public GitHub repository, e.g. `underwritepro`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md`.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then save.
6. Wait for the deployment URL to appear.

## Important limitations
This is a student demonstration, not a production insurance system. It has no real authentication, server, database, secure file storage or real underwriting logic. Login/register is listed in the assignment brief but not implemented as secure authentication in this frontend-only version. All risk scores and policy records are illustrative and must not be used for real insurance decisions. Do not enter real personal, financial, health or identity information.

## Task details
- Task ID: WD-INS-005
- Project: UnderwritePro
- Domain: Underwriting / Insurance
- Company named in task brief: Data Alcott Systems
