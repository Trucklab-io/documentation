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

- Getting started and workspace setup
- Clients, drivers, and trucks
- Daily and recurring planning
- Planning review and publication
- Roles, permissions, troubleshooting, and terminology

The API reference will be added separately when the API becomes public.
