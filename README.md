# Backed Docs

This repository is the source of truth for Backed documentation.

## Structure

- `docs.json`: site configuration
- `index.mdx`: landing page
- `overview/`: platform-level explanation and concepts
- `guides/`: founder, investor, and lifecycle guidance
- `operations/`: operator workflows, checklists, and incident handling
- `technical/`: architecture, deployments, runtime, and integrations
- `trust/`: trust assumptions and risk boundaries
- `support/`: FAQ

## Publishing

1. Use this repository as the docs source.
2. Publish on a dedicated docs domain such as `docs.backed.fi`.
3. Set `NEXT_PUBLIC_DOCS_URL` in the frontend app so `/documentation` redirects to the published docs.

## Editing standard

Keep the documentation platform-first. Product explanation, operational guidance, technical reference, and risk disclosure should remain clearly separated.
