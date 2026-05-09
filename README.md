# Backed Docs

This repository is the source of truth for Backed documentation.

## Structure

- `docs.json`: site configuration
- `index.mdx`: landing page
- `overview/`: platform-level explanation and concepts
- `guides/`: agent, investor, lifecycle, and economics guidance
- `technical/`: architecture, deployments, runtime, and integrations
- `trust/`: curation boundaries, security assumptions, and risk boundaries
- `support/`: FAQ

## Publishing

1. Use this repository as the docs source.
2. Publish on a dedicated docs domain such as `docs.backed.fi`.
3. Set `NEXT_PUBLIC_DOCS_URL` in the frontend app so `/documentation` redirects to the published docs.

## Editing standard

Keep the documentation platform-first. Product explanation, participant guidance, technical reference, and trust disclosure should remain clearly separated.
