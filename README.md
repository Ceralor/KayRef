# KayRef

A simple [11ty](https://www.11ty.dev/)-based ref sheet display site for Kay Ohtie.

## Preview & Build

- Start a local live preview with hot reload via `npm run dev` or `eleventy --serve`.
- Build via `npm run build` or simply `eleventy`. Built output is written to `dist/`.

Images are automatically resized to 600px and 1200px widths, if larger, with `eleventy-img`. `<img>` tags generated from Markdown are updated with the new sizes. Original images are copied as-is to `dist/images` alongside the resized versions.

## Github Pages

Auto-builds for Github Pages. Set your custom domain in the CNAME file, and after the first build runs, set Pages to deploy from a branch. Choose `gh-pages`.