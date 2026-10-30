# Cinemanwala

**Your City. Your Creator. Your Story.**

Cinemanwala is a mobile-first frontend prototype for a hyperlocal cinematic creator marketplace. Customers can explore creators, filter demo listings, request direct bookings, and post shoot requirements. Creators can submit an expression of interest.

## Run locally

This is currently a static frontend prototype with no backend. You can open `index.html` directly, or run a local server:

```bash
python -m http.server 5500
```

Then visit http://localhost:5500.

## Current prototype features

- Responsive landing page and category browsing
- Dark/light theme toggle (preference saved in browser)
- Demo creator cards with search, budget, distance and sorting filters
- Direct booking request form
- Post-a-shoot quotation request form
- Creator interest form
- Demo form submissions saved in browser localStorage
- Accessible SVG brand mark

## Important limitations

- Creator listings and prices are illustrative demo data, not real providers.
- Forms save only in the current browser; they do not contact creators or an admin.
- Authentication, database, real geolocation, maps, chat, payments, verification and notifications are not connected yet.
- Do not accept real customer payments or represent demo profiles as verified providers.

## Next development phase

1. Set up GitHub repository and deployment.
2. Choose backend/database and implement authentication and role permissions.
3. Replace demo listings with creator records from the database.
4. Implement PostGIS nearby search and service-radius matching.
5. Implement booking and quotation workflows with concurrency safeguards.
6. Add creator/admin dashboards, moderation, privacy, payments and tests.

## Project structure

```text
cinemanwala/
├── assets/
│   └── logo-mark.svg
├── index.html
├── styles.css
├── app.js
├── README.md
├── package.json
└── .gitignore
```
