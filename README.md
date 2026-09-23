# GRPS Written Process Collaborative

Static GitHub Pages site. Upload the contents of this folder to the root of a GitHub repository, then enable Pages under Settings → Pages → Deploy from a branch → main / (root). The site uses local JSON and requires no backend or paid services.

**Review notice:** The 54 DOCX files are working drafts. The historical master index contains 47 records, not 54; 43 site entries matched uniquely to its indicator descriptions. Unmatched entries are shown as not validated. No process is presented as approved based on the Wix CMS label. Search, filters, cards, detail pages and download links are client-side. Editing status requires updating processes.json and republishing.


## GRPS logo and meeting evidence
The site references the official GRPS logo at https://grps.org/downloads/infohost/communications-external-affairs/grps_district_logo.png. It requires the image to remain available on the GRPS website; if district policy requires a local asset, place an authorized copy in this package and update `index.html`.

The Meeting records page includes downloadable agenda, minutes/notes and sign-in templates plus an evidence register. Retain agenda and minutes/notes for each process update meeting. If notes do not identify attendees, retain a separate sign-in sheet. **Do not upload completed sign-in sheets or sensitive meeting records to this public GitHub repository.** Store originals in approved restricted district storage. The CSV form downloads a local entry and does not synchronize records across users.


## Fixes in this release
- Master index download moved to home page (and remains in the management dashboard), removed from each individual process page and top navigation.
- Each process has one direct DOCX download pointing to a file in `documents/`. On a published site, a missing document is flagged rather than silently linking to a 404.
- Upload **all** contents, especially the entire `documents/` folder. GitHub's web uploader may omit folders if only individual files are selected. If an older version is deployed, overwrite the files and verify `documents/` contains 54 DOCX files in GitHub.
- Header uses the district's official GRPS logo URL. The image requires that the GRPS server makes the URL available; if unavailable, a GRPS text fallback appears. To make it independent of the district server, supply a local copy of the approved logo.
