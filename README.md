# Backed Docs

This repository is the source of truth for Backed documentation.

## Structure

- `docs.json`: Mintlify site configuration
- `index.mdx`: landing page
- `overview/`: platform-level explanation and concepts
- `guides/`: founder, investor, and lifecycle guidance
- `operations/`: operator workflows, checklists, and incident handling
- `technical/`: architecture, deployments, runtime, and integrations
- `trust/`: trust assumptions and risk boundaries
- `support/`: FAQ

## Mintlify setup

1. Create a Mintlify project connected to this repository.
2. Use the repository root as the docs root.
3. Publish on a dedicated docs domain such as `docs.backed.fi`.
4. Set `NEXT_PUBLIC_DOCS_URL` in the frontend app so `/documentation` redirects to the published docs.

## Local preview

If you want to preview locally with the Mintlify CLI, run it from the repository root:

```bash
npx mintlify dev
```
