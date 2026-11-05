# entity-viewer

Viewer for contracted-entity statements, Arabic and right-to-left. It reads xlsx, xls and csv files, previews each sheet and prints.

## Limits

- Nothing is kept between sessions; the page uses neither `localStorage` nor IndexedDB.

## Network and install

No network calls after load; loads SheetJS and Google Fonts from a CDN. Not installable; no service worker.
