# AGENTS.md

Guidance for contributors and coding agents working on the Trucklab documentation.

## About this project

- This is the public Trucklab documentation site, published with Mintlify.
- Pages are MDX files with YAML frontmatter.
- Configuration and navigation live in `docs.json`.
- The current documentation covers the Affretio dispatch workspace.
- The public API is intentionally out of scope until Trucklab announces it.

## Terminology

- Use **Trucklab** for the company and documentation site.
- Use **Affretio** for the dispatch workspace shown in the product UI.
- Use **workspace** for the active customer environment. Use **account** only when
  matching an exact UI or error message.
- Use **client** for a customer organization managed by a transport company.
- Use **driver**, **truck**, **trip**, **planning**, **planning version**, and
  **recurring trip** consistently.
- Preserve exact UI labels in bold. Some Planning labels are currently in French;
  do not translate a button name that users must locate in the interface.

## Writing style

- Use active voice and second person ("you").
- Keep sentences concise and use sentence case for headings.
- Start task pages with the outcome, prerequisites, and required role.
- Format UI labels in bold: Select **New driver**.
- Format file names, commands, paths, and code references as code.
- Prefer ordered steps for workflows and tables for exact role or status mappings.
- Do not claim that an email, notification, or background job occurs unless the
  product behavior confirms it.

## Content boundaries

- Document supported customer workflows and user-visible behavior.
- Do not publish private API endpoints, database details, infrastructure, secrets,
  internal admin procedures, or security implementation details.
- Do not include real customer, driver, vehicle, or planning data in examples.
- Do not document speculative or unreleased features.
- Keep screenshots optional and remove sensitive information before committing them.
- Store screenshots under `images/<area>/`, use descriptive kebab-case names, and
  add useful alternative text wherever the image appears.
- Do not use a production or customer workspace to produce documentation screenshots.

## Contribution workflow

1. Read the relevant product UI or source before changing behavior-specific guidance.
2. Keep navigation paths in `docs.json` aligned with the MDX files.
3. Preview with `mint dev` when layout changes.
4. Run `mint validate` before requesting review.
5. Use a pull request so content and navigation can be reviewed together.
