# Trucklab documentation

Public product documentation for Trucklab's Affretio dispatch workspace, built
with [Mintlify](https://mintlify.com).

The documentation is curated around customer workflows. It intentionally excludes
the private Trucklab API and internal operational procedures.

## Local development

Install the Mintlify CLI with Node.js 20 or later:

```bash
npm install --global mint
```

Start a local preview from the repository root:

```bash
mint dev
```

Validate configuration, navigation, links, and MDX:

```bash
mint validate
```

## Publishing

Changes are reviewed through pull requests. Merging to `main` triggers the
Mintlify production deployment through the connected GitHub App.

## Documentation scope

- Authentication, first-time setup, and workspace membership
- Company settings, dashboard indicators, and tariff grids
- Clients, drivers, driver absences, and trucks
- Daily planning, recurring trips, review, publication, and history
- Pre-invoicing, alerts, subcontracting, tracking shares, and route ETAs
- Roles, permissions, troubleshooting, and terminology

## Screenshots

Screenshots belong under `images/` and must use fictional or empty-state data.
Before adding a screenshot, confirm it contains no customer names, personal data,
vehicle registrations, private links, invoice references, or planning details.

The API reference will be added separately when the API becomes public.
