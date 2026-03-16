# Plyra Docs

This repository contains the official documentation for Plyra, the infrastructure layer for agentic AI.

## Architecture

Pages are built using [Mintlify](https://mintlify.com) and written in MDX.

- **Content**: Located in the root and `guard/` directories.
- **Branding**: Configured in `docs.json` using Plyra's brand system (Teal/Void).
- **Snippets**: Reusable components in the `snippets/` directory.

## Development

To preview the documentation locally, install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the dev server from this directory:

```bash
mintlify dev
```

Visit `http://localhost:3000` to see your changes.

## Validation

Before pushing, check for broken links:

```bash
mintlify broken-links
```
