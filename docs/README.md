# cd-schemas

JSON Schemas и OpenAPI для Coffee Digital.

## Содержимое

- `mqtt/` — топики, матрица QoS/retain
- `jsonschema/` — описания команд и телеметрии
  - `manifest/` — схемы RPK и firmware
  - `telemetry/` — схемы кадров для телеметрии
- `openapi/` — спецификация SaaS API

## Правила

- Каждое сообщение имеет `schema_version`.
- Совместимость контролируется через SemVer.
- Используется во всех репозиториях как submodule.
