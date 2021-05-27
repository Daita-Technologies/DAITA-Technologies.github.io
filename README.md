# Documentation
Guides and quickstarts for integrating DAITA's products.

## Preview
MkDocs includes a live preview server, so we can preview our changes as we write our documentation. The server will automatically rebuild the site upon saving. Start it with:
```
mkdocs serve
```
Point the browser to [localhost:8000](http://localhost:8000).
## Building the Site
We can build a static site from our Markdown files with:
```
mkdocs build
```

## Published Site
We use [GitHub Pages](https://pages.github.com/) and [GitHub Actions](https://github.com/features/actions) to automatically deploy our project documentation. Every commit to the `main` branch leads to an automatic redeployment. The exact GitHub Actions workflow is configured in [`ci.yml`](https://github.com/Daita-Technologies/documentation/blob/main/.github/workflows/ci.yml). The final published site can be found here [docs.daita.tech](https://docs.daita.tech).

# References
[1] https://www.mkdocs.org/

[2] https://squidfunk.github.io/mkdocs-material/
