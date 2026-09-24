# .viupdate package format

A `.viupdate` file is a ZIP archive.

Required file at archive root:

`update-manifest.json`

Example:

```json
{
  "schema": 1,
  "version": "0.12.0",
  "delete": []
}
```

All other files are copied relative to the Vi Optimizer runtime directory.

The public `latest.json` feed contains the release asset URL, SHA-256 and optional byte size. Vi Optimizer only accepts package URLs under:

`https://github.com/Zelv-rus/ViOptimizer-Updates/releases/download/`
