# Classroom Tools

Small single-page tools for teaching, served with GitHub Pages at https://tools.pulseclassroom.com.

| Tool | Path |
|---|---|
| Exam Room Clock | `/exam-clock/` |
| Practical Station Timer | `/practical-timer/` |

Each tool is one self-contained `index.html` with no build step. To add a tool, make a new folder with an `index.html` and add a link to it on the root `index.html`.

## Hosting

- GitHub Pages: deploy from the `main` branch, root folder.
- `CNAME` holds the custom domain. DNS: a CNAME record for `tools` pointing at `<github-username>.github.io`.
- `.nojekyll` tells Pages to serve the files as-is.
