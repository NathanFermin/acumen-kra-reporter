# IDP — Individual Development Plan Tool

A single-page tool for Acumen's Year End Review. An employee picks a role,
fills in their self-assessment (ratings + comments), and generates a
fillable PDF where the supervisor can add their own ratings and comments.

## Run it
No build step. Open `index.html` in a browser, or use the VS Code
**Live Server** extension (right-click `index.html` → Open with Live Server).
Live Server is recommended because the PDF library loads from a CDN.

## Structure
- `index.html` — the whole app (HTML, CSS, JS in one file for now)

## Roadmap
- Split KPI into an editable field (KPI is user input per the meeting minutes)
- Populate roles + KRAs from the Project Y inventory (pending from HR)
- Persist submissions to MongoDB (needs a backend)
