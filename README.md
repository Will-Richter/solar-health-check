# Solar Health Check

A phone-first web app with two modes:

- **My system** – a ground-level self-check for homeowners (inverter reading, visual checks, photos), with a history, an output trend and a next-check date.
- **Technician** – an on-site health check report: string readings against expected output, a visual inspection, photos and a PDF report.

Everything is saved in the browser on the device that opens it. There is no server and no login.

## Files

- `index.html` – the whole app. Installer details are in `window.SHC_CONFIG` near the bottom.
- `sw.js`, `manifest.webmanifest`, `icon-*.png` – let it be added to a phone's home screen and opened without signal.

## Scope

The technician report is a visual, non-invasive health and performance check. It is not an electrical compliance certificate.
