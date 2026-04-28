# DocFlow Manifest

Public manifest за update discovery от DocFlow инстанции. Auto-updated от
[Tockyto/docflow](https://github.com/Tockyto/docflow) release workflow.

## Файлове

- **`manifest.json`** — текущата стабилна версия + image references + changelog URL
- **`changelog.json`** — full changelog (mirror на private repo)

## Schema (manifest.json)

```json
{
  "latest": "1.9.3",
  "released_at": "2026-04-28T17:30:00Z",
  "min_compatible": "1.9.0",
  "image": "ghcr.io/tockyto/docflow:1.9.3",
  "updater_image": "ghcr.io/tockyto/docflow-updater:1.9.3",
  "changelog_url": "https://raw.githubusercontent.com/Tockyto/docflow-manifest/main/changelog.json",
  "schema_version": 1
}
```

## Не git-pull/edit-вай ръчно

Този repo е managed automatically. Ръчни промени се overwrite-ват при
следващия release.
