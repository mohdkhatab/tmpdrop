# Architecture

TmpDrop is a small web app with three parts:

- **Frontend** — the upload and download pages users interact with.
- **API** — endpoints under `api/` that accept uploads and serve downloads.
- **Storage** — Firebase-backed storage/database for file metadata and expiration.

When a file expires, its metadata and stored content are removed.
