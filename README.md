# Home Visit Safety & Care — Website Prototype

A responsive, single-page website prototype for a physiotherapist home-visit safety and clinical documentation concept.

## Run locally
1. Extract this folder.
2. Open `index.html` in a modern browser.
3. For GPS permissions, use localhost or a secure HTTPS website. GPS may not work when opening the file directly.

## Features in this demo
- Dashboard and sample appointments
- Add booking and select visit
- Check-in, countdown timer, and check-out
- Silent SOS simulation with event log
- Browser-generated loud alarm with stop button
- Optional browser GPS permission request
- Trusted contacts
- Patient records and SOAP notes
- Exercise / next-session plan
- Confidential safety flag
- Safety history and JSON export
- Local browser storage

## Important limitations
This is a frontend demonstration only. It does not send real SMS/push alerts, contact police/emergency services, securely store medical records, provide reliable background location tracking, or authenticate users. Do not enter real patient data. The browser's local storage is not a secure database. A production version requires a backend, authentication, secure storage, consent, access control, audit logs, and tested integrations for notifications and emergency escalation.

## Publish with GitHub + Vercel
1. Create/sign in to GitHub.
2. Create a new repository (e.g. `home-visit-safety-demo`).
3. Upload `index.html` and `README.md` to the repository root (or use GitHub Desktop).
4. Create/sign in to Vercel and choose **Add New → Project**.
5. Import your GitHub repository.
6. For this plain HTML website, use the default/Other preset if asked; no build command is needed and the output/root directory is the repository root.
7. Click **Deploy**. Vercel will provide a public HTTPS URL you can share.
8. After editing files on GitHub, Vercel redeploys automatically.

Alternative: use GitHub Pages from the repository's Settings → Pages, select deployment from the `main` branch and `/ (root)`, and save. Wait for the published URL to appear.

## Suggested next step
Before claiming that the website provides real safety protection, implement and test a backend that can securely receive events and notify approved contacts. Do not represent a demo alert as a real emergency response.
