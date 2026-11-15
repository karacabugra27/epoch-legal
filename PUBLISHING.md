# Publishing the legal pages

These files are the source of the GitHub Pages site the app links to (`VITE_LEGAL_URL`, default
`https://karacabugra27.github.io/epoch-legal`).

1. Fill `contact_email` and `server_location` in `_config.yml`.
2. Copy this folder's contents to the root of a public repo (for example `epoch-legal`).
3. Repo settings → Pages → deploy from the `main` branch, root folder.
4. If the URL differs from the default, set the `LEGAL_URL` repository variable in the app repo
   (the deploy workflow passes it to the web build as `VITE_LEGAL_URL`).

Paths the app opens: `/privacy`, `/terms`, `/en/privacy`, `/en/terms`.
When a page changes in a way users must know about, update its date and tell users in the app.
