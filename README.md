# ShapeBit Docs

This repository contains the Jekyll layout and GitHub Pages deployment for the
ShapeBit OS documentation.

Documentation content is maintained in the
[ShapeBit Docs Wiki](https://github.com/shapebit-software/docs/wiki) and
published at [shapebit.software](https://shapebit.software/).
Published page paths are normalized to lowercase, for example
`/system-design/`.

## Local development

Install [mise](https://mise.jdx.dev/), then run:

```bash
mise install
mise run serve
```

This clones the Wiki into the ignored `wiki/` directory and serves the site at
`http://localhost:4000/`.
