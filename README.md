# PANDOR docs

The player docs for PANDOR, published at [docs.pandor.gg](https://docs.pandor.gg) with [Mintlify](https://mintlify.com).

## Edit and preview

```sh
npx mint@latest dev            # preview at http://localhost:3000
npx mint@latest validate       # check docs.json and every page
npx mint@latest broken-links   # check internal links
```

`docs.json` holds the navigation, theme and logos. Pages are MDX, grouped by folder: `planet/`, `war/`, `ore/` and
`wallet/`.

## Publishing

Mintlify deploys every push to `main`.
