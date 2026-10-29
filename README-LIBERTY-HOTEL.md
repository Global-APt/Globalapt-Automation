# LIBERTY HOTEL — Interactive Hospitality Demo

Static HTML/CSS/JavaScript prototype for presenting the proposed LIBERTY HOTEL guest website and hospitality operations dashboard. The visual direction uses editorial serif headlines, restrained forest-green and brass accents, warm neutral surfaces, generous spacing and photography-led room presentation.

## Run locally
Open `index.html` in Chrome or Edge. No Node.js build step is required.

## Demo areas
- Public hotel website: Home, Rooms & Suites, Gallery, Services, Contact
- Responsive navigation, keyboard focus states, descriptive image text, reduced-motion support and accessible form labels
- Mobile-first layouts and performance-minded image loading
- Responsive date-and-room preference strip plus reservation estimate with date validation (not a live booking)
- Larger, more readable typography using Source Sans 3 for interface text and Libre Baskerville for formal headings
- Department workspace navigation for Front Desk, Housekeeping, Maintenance, IT Support, Inventory, Accounting, Management and Owner oversight
- Accounting demonstration with sample revenue/settlement lines, draft expense entry and CSV demo export
- Owner oversight view aggregating sample service requests and low-stock alerts
- Guest request portal with request references and status tracking
- Management overview with sample occupancy and room status
- Owner overview for cross-department visibility (sample data only)
- Front desk room board with clickable demo room statuses
- Housekeeping, maintenance and IT request queues
- Inventory register with sample stock receipt actions
- Smart systems concept screens for door access, climate, lighting and internet

## Important limitations
All data is demonstration data held in the current browser session. Refreshing the page resets changes. Reservations are not confirmed; there is no payment processing, live availability, authentication, backend database, staff notifications, QR token provisioning, or connected lock/Wi-Fi hardware. Hotel prices, room count, contact details and dashboard metrics are illustrative placeholders. Images are served from Unsplash and need an internet connection.

## GitHub Pages
This project is on the `liberty-hotel-demo` branch of `Global-APt/Globalapt-Automation`. To publish it, open the repository's **Settings → Pages**, choose **Deploy from a branch**, select branch `liberty-hotel-demo` and folder `/(root)`, then save. GitHub will show the public Pages URL after deployment.

## Production next steps
1. Confirm brand assets, actual rates, room inventory and hotel policies.
2. Implement authentication, permissions, PostgreSQL persistence and audit history.
3. Add live reservation availability, payment provider and guest notifications.
4. Connect OPERA only through an authorised integration route.
5. Validate compatible smart-lock and Wi-Fi controller integrations.
6. Test security, backups, failure recovery and staff workflows before production use.
