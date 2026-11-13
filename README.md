# PDF to CBZ

A lightweight, client-side web app that converts PDFs into CBZ comic archives. Add up to 40 PDFs per batch; each PDF becomes its own CBZ containing one numbered JPEG image per page.

## Run it

Open `index.html` in a modern browser, or serve this directory with any static web server. The app loads PDF.js and JSZip from public CDNs, so an internet connection is needed when opening it. Your PDF contents are processed locally in your browser and are not uploaded to a server.

## Batch behavior

The app accepts up to 40 PDFs in a single batch and converts up to two files concurrently to limit browser memory use. Choose standard, high, or very high rendering resolution and JPEG quality before starting. Download each CBZ from its row. Failed files can be retried by pressing **Convert PDFs** again.

Large PDFs can consume substantial memory and conversion time. Keep this page open until conversion finishes.
