# Global Logistics Shipment Inventory

Admin portal and APIs for managing vehicle shipments from yards through vessels to ports. Built for high-volume logistics operations with role-based admin tools, bulk workflows, analytics, and AWS-backed photo storage.

**Repository:** [github.com/abdul-hannan-SE/global_logistics_inventory](https://github.com/abdul-hannan-SE/global_logistics_inventory)

**Screenshots folder:** [github.com/abdul-hannan-SE/global_logistics_inventory/tree/main/sreenshots](https://github.com/abdul-hannan-SE/global_logistics_inventory/tree/main/sreenshots)

> The directory is named `sreenshots` in the repo (typo). Images in this README use paths relative to the repository root so they render on GitHub after you copy this file to `README.md`. If you rename the folder to `screenshots`, update every `./sreenshots/` path below.

---

## Features

- **Shipments** — Filter by date, job number, chassis, vessel, POD, customer, yard, and status; add records; export; row actions; photo counts tied to storage.
- **Bulk workflows** — Multi-select for assign vessel, gate out / status, bulk photo download, and related batch actions.
- **Vessels** — Vessel records with job numbers, shipping lines, ETD, POD, and maintenance of large vessel lists.
- **Customers** — Admin customer directory, credentials, and search.
- **Analytics** — Overview metrics and deeper analytics views (including gate-style reporting where enabled).
- **Customer portal** — Customer-facing dashboard (search, filters, export) for their own shipment visibility.
- **Photo management** — Per-shipment galleries with upload limits and AWS-backed media.
- **Authentication** — Login and session flows for admin and customer roles.
- **Migration** — Data migration utilities where exposed in the admin UI.

---

## Tech stack

| Layer     | Technologies                        |
| --------- | ------------------------------------- |
| Runtime   | Node.js                               |
| API       | Express.js, REST                      |
| Database  | MongoDB                               |
| Media     | AWS (e.g. S3)                         |
| Admin UI  | React (adjust to match your codebase) |
| Deploy    | Vercel or your host                   |

---

## Screenshots

All images live under [`sreenshots/`](https://github.com/abdul-hannan-SE/global_logistics_inventory/tree/main/sreenshots) on the default branch.

| File | What it shows (high level) |
| ---- | -------------------------- |
| `shipments.png` | Shipments grid and primary admin list |
| `02-shipments-bulk-download-photos.png` | Bulk selection and photo / download oriented workflow |
| `05-vessels.png` | Numbered vessel export / sample vessel UI |
| `vessels.png` | Vessel management table |
| `customer.png` | Customer admin listing |
| `customer dashboard.png` | Customer-facing dashboard |
| `analytics.png` | Analytics overview |
| `analytics-1.png` | Additional analytics / charts view |
| `photos aws.png` | Photo management with cloud storage context |
| `login.png` | Sign-in screen |

Preview (paths are relative to repo root; same layout as on [GitHub](https://github.com/abdul-hannan-SE/global_logistics_inventory/tree/main/sreenshots)):

![Shipments](./sreenshots/shipments.png)

![Bulk shipments & photos](./sreenshots/02-shipments-bulk-download-photos.png)

![Vessels (05)](./sreenshots/05-vessels.png)

![Vessels](./sreenshots/vessels.png)

![Customers](./sreenshots/customer.png)

![Customer dashboard](./sreenshots/customer%20dashboard.png)

![Analytics](./sreenshots/analytics.png)

![Analytics (alternate)](./sreenshots/analytics-1.png)

![Photos & AWS](./sreenshots/photos%20aws.png)

![Login](./sreenshots/login.png)

---


## Author

**Abdul Hannan** — Backend & full-stack development.
