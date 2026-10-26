# DesignPro

A local-first BOQ studio for Indian interior design teams, built with React 18, Vite, Tailwind CSS 3, React Router, Lucide, and jsPDF.

## Run locally

```sh
npm install
npm run dev
```

Create a production bundle with `npm run build`, then preview it with `npm run preview`.

## Data and privacy

Firm details, project BOQs, revisions, templates, and preferences are stored in this browser's `localStorage`. No backend or account is used. Browser storage is device and browser specific. Share links encode a read-only snapshot in the URL, so anyone with the link can view that snapshot.

## Included flows

- Project dashboard, project creation from blank or saved template, search, status, and delete
- Room-based BOQ editor with categories, quantities, rates, margins, GST, notes, approvals, photos, and vendor quotes
- Revision snapshots, activity log, room totals, and payment milestones
- HTML invoice preview, shareable read-only view, and jsPDF export
- Firm profile, logo, currency, reusable templates, and defaults
