# FieldFlow HR MVP

A dependency-free, responsive HR field-force management prototype. It runs as a static site and uses browser `localStorage` as an intentionally isolated data adapter (`store` in `app.js`) so the adapter can later be replaced with API calls.

## Run

Open `index.html` in a modern browser, or serve the folder with any static server (for example `python -m http.server`). Camera and geolocation permissions generally require `localhost` or HTTPS.

Use `employee@fieldflow.test` / `demo123` for the employee experience, or `admin@fieldflow.test` / `demo123` for the admin dashboard. The demo supports attendance with optional selfie capture, GPS, visits, orders, collections, leave requests, approvals, summary reports, and CSV export.

This prototype stores demo data locally in the current browser only. Do not use it for real employee data until authentication, authorization, encryption, retention, and a server-side database are implemented.

## Repository

This MVP is built in the repository's existing hackathon starter project. See [hackathon.md](./hackathon.md) and the [development exercises](./content/0-get-started.md) for the broader project context.

## License

This project is licensed under the terms of the MIT open source license. See [LICENSE.txt](./LICENSE.txt).
