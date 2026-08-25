# ACN Development — Resource Versions & Metadata

Centralized remote metadata and version registry for all **ACN Development** FiveM resources.

This repository is used by the in-game remote version checking system (`server/version.lua`) to inform server owners of available updates, changelogs, and critical patches.

## Structure

```text
versions/
├── acn_bridge.json
├── acn_inventory.json
├── acn_billing.json
└── [resource_name].json
```

## Raw Endpoint Format

```text
https://raw.githubusercontent.com/acnesia/versions/main/versions/<RESOURCE_NAME>.json
```
