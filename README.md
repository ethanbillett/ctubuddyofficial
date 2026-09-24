# CTU Buddy

A standalone student community website by **Ethan Gareth Billett**. Built with HTML, CSS and vanilla JavaScript, with a blue, white and lime interface that adapts to smaller screens.

## Open the project

1. Extract the ZIP file.
2. Open the `CTU-Buddy` folder.
3. Double-click `index.html` in a modern browser such as Chrome, Edge or Firefox.
4. Keep `index.html`, `styles.css`, `script.js` and `assets/` together.

No installation, build command, internet connection or live website is required for the included demo. If your browser restricts storage when opening files directly, use VS Code's Live Server extension to preview it on your own computer. This is still local and does not publish the website.

## What works

- **Home:** local profile, greeting, next upcoming weekly class and live totals.
- **Navigation:** section links and a collapsible mobile menu.
- **Profile:** edit the display name used for new posts, replies and resources. This is not an authentication system.
- **Timetable:** add, edit and remove classes; filter by weekday; reject invalid times and overlapping classes; print the full week.
- **Discussions:** create posts, search, filter by topic, like/unlike, add replies and delete discussions.
- **Resources:** add website links or attach small PDF, text and image files; download attachments; search; bookmark and remove resources.
- **Contact:** validate and save enquiries locally, then view or delete them. No messages are sent.
- **Backup:** export your current data as JSON and restore a valid backup after confirming replacement.
- **Reset:** restore the sample profile, timetable, discussions and resources after confirmation.

## Files

```text
CTU-Buddy/
  index.html           Page content, forms and dialogs
  styles.css           Layout, colours, mobile and print styles
  script.js            Interactive features and browser storage
  assets/
    favicon.svg        Local site icon
  README.md            Instructions
```

## Local demo limits

Everything belongs to the current browser on this computer. There is no server, database, actual login, multi-user sharing or email delivery. The name on a post is a local display name. You can remove any sample content because this is a single-user demonstration.

Data is saved in browser localStorage under `ctu-buddy-project-v1`. Moving the folder, changing browsers, clearing site data or using private browsing can affect persistence, especially when opening a file directly. Export a backup before moving the project or resetting it. Enquiries and uploaded files are part of that backup, so avoid entering sensitive information.

Each attachment can be up to 500 KB. Combined encoded attachments are limited to approximately 2 MB of original file data; browser storage limits may impose a lower limit. Supported attachments: PDF, TXT, PNG, JPG, JPEG and WebP. Choose a link or an attachment for each resource. Links to external websites require internet access; the three included reference downloads work offline.

The demo supports up to 200 classes, 200 discussions, 100 replies per discussion, 100 resources and 200 enquiries. It reports storage errors instead of claiming that unsaved changes succeeded. Imported backups are validated before being saved.

The timetable repeats weekly from Monday to Friday. Sample classes are illustrative and are not an official CTU schedule. The team section credits Ethan Billett, Dariane Meyer, Sawongwa Thambo and Jason Cameron from the original project. This is a student portfolio project, not an official CTU service.

## Editing

Change content in `index.html`, styles in `styles.css`, and behaviours or initial sample data in `script.js`. Existing browser data takes priority over edited sample data; use Reset demo after exporting a backup to load a changed sample.

## Checks performed

JavaScript syntax, HTML IDs, local asset links and section targets were checked. Script checks covered initial rendering, persistence, storage failure rollback, backup validation, unsafe link and file-type rejection, text escaping, replies, search, bookmarks and next-class calculation. A browser rendering engine was unavailable for a full visual and interaction check; native dialogs, file selection, downloads and print should also be tried in your browser.

## Author

Ethan Gareth Billett
