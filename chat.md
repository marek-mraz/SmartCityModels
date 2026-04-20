# Actions Taken
- Finalized `.github/workflows/pages.yml` to publish the schema registry.
- Completed the Python script that crawls the `schema-registry/domains` directory.
- The script automatically extracts the `typeName` (folder name) and relative `path` for every valid schema found.
- Configured the workflow to deploy the `schema-registry` directory as a static site.

# Next Recommendations
- Merge these changes to the `main` branch to trigger the first deployment.
- Verify the `index.json` output by visiting `https://<user>.github.io/<repo>/index.json`.
- Configure your backend `SCHEMA_REGISTRY_URL` environment variable to point to the base URL of the published Pages site.
- Removed "nazov" (name) from `Projekt` required fields and `Zariadenie` UI schema as requested.