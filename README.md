# RealEst — Lead Thank-You Page

**The confirmation page shown after a visitor submits the RealEst Salesforce Web-to-Lead form.**

This is one of three small repos that make up a Salesforce web-form demo for a fictional real-estate company:

| Repo | Role |
|---|---|
| [webservice](https://github.com/AliAzamat/webservice) | The Web-to-Lead and Web-to-Case forms |
| **thankslead** | Thank-you page after a lead submission (this repo) |
| [thankstocase](https://github.com/AliAzamat/thankstocase) | Thank-you page after a support case submission |

The lead form's `retURL` points here (`aliazamat.github.io/thankslead/`), so Salesforce redirects visitors to this page after creating the Lead. It shows the RealEst header and a confirmation message, with a link back to the form.

## Files

- `index.html` — the page
- `thanks-to-case.css` — styles (shared design with the case thank-you page)
- `logo.png` — RealEst logo

Open `index.html` in a browser to view it, or host the folder on GitHub Pages.
