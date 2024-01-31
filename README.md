# Example Docusaurus multi-instanced site with versioning

This is a very basic example of a Docusaurus project that uses multi-instance and versioning.

The site has three documentation sets (doc sets): the default `docs`, an SDK doc set (`sdk`), and an API doc set (`api`).

- Default `docs`
  - Uses the `classic` preset.
  - Doesn't need a unique `id`.
  - Uses the `sidebarDefault.js` sidebar.
- SDK docs
  - Uses an instance of the `@docusaurus/plugin-content-docs` plugin.
  - Sidebar: `sidebarSDK.js`
  - Content location: `sdk`
  - Plugin instance ID: `sdk`
- API docs
  - Uses an instance of the `@docusaurus/plugin-content-docs` plugin.
  - Sidebar: `sidebarAPI.js`
  - Content location: `api`
  - Plugin instance ID: `api`


## Quick start

To get the example site up and running:

1. Clone this repo.
2. Navigate to the `my-website` folder.
3. Run `pnpm start`.

