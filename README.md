# nimadehkordi.github.io

Personal site. All content lives in `cv.json` ([JSON Resume](https://jsonresume.org/schema) format) — edit it and the site updates on next load. No build step.

- `projects[].type`: `"featured"` → Selected work cards, `"open-source"` → Open source list
- The `work` entry without `endDate` is shown as the current role
- `basics.x-*` fields are site-only: tagline, focus, years of experience, `x-cvPdf` (path/URL to a PDF; shows the Download CV button when set)
