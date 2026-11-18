# AmiWho — interactive prototype

Open **`amiwho-app.html`** in a modern browser (double-click; no build or server needed).

## Controls (top bar)

- **Device** — iPhone, iPad, or both side by side. The iPad can be rotated to landscape, and its sidebar collapses to an icon rail with the panel button at the top.
- **Appearance** — light and dark mode.
- **Demo account** — customer, client, admin or staff. Roles decide which app opens.
- **Data state** — Live, Empty, Loading or Error for the Library and the client Overview.
- **Sign out / Reset** — reset navigation or the whole demo.

## What works

- Sign in (email/password), create account, Sign in with Apple → Face ID sheet.
- Admin workspace chooser and role-based access to one or both apps.
- Document store: search, category filter, sort, detail, buy once, add to bundle, subscribe.
- Checkout with card or Apple Pay sheet, purchase success, download and Library.
- Library downloads, progress, “new version available”, update, secure viewer with an expiring link and page navigation.
- Notifications, read/unread, account, plan and notification settings.
- Admin dashboard, document upload/version and price editing, user roles.
- Client dashboard: overview, financial detail with range and compare, cash flow, KPIs, projects, project detail, tasks, settings.
- Admin client tools: manual data entry with live margin calculation, and the four-step CSV import.

Sample data is AUD hospitality data for Marlow & Fern.

`amiwho-mockups.html` is the earlier still-image mockup board, kept for reference.

## Design direction

The app follows the supplied AMIwho brand system: Dark Paradise for uppercase mastheads and document titles, Work Sans for interface and figures, charcoal `#232222`, champagne `#DDC6A5`, cream `#F4E6CA` and off-white `#EEECEA`, with an antique-gold `#A57C3F` accent. The signature is the AMIwho wordmark, the AW oval, the double gold rule over mastheads, book-spine covers and the black marble sign-in panel.

## Hosting

The site is static. `vercel.json` rewrites `/` to `amiwho-app.html`, so importing this repository into Vercel and leaving the framework preset as “Other” is enough; no build step.
