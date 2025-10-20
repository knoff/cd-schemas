<!-- markdownlint-configure-file {"MD041": false} -->

## [2025-10-13 13:46 GMT+3]

### docs: Create README.md

Создан базовый `README.md` для репозитория `cd-schemas`.
Добавлено краткое описание назначения: хранение JSON Schemas, OpenAPI и MQTT-топиков.

---

## [2025-10-16 10:46 GMT+3]

### chore: workspace setup, formatting & linting, gitignore

Настроено окружение проекта.
Добавлены `.editorconfig`, `.gitattributes`, `.gitignore`, `.markdownlint.json`, `.pre-commit-config.yaml`, `.prettierrc.json`, `.github/workflows/lint.yml`.
Включён pre-commit с проверками `yaml`, `json`, `markdownlint`, `prettier`.

---

## [2025-10-16 13:13 GMT+3]

### chore: directory structure

Созданы каталоги и базовые JSON Schema:
`jsonschema/manifest/` (RPK, firmware) и `jsonschema/telemetry/` (core.frame, pump.frame).
Добавлены пустые схемы-заглушки `{}` и файл `docs/README.md`.

---

## [2025-10-16 13:47 GMT+3]

### docs: Определение структуры документации

Добавлены `README.md`, `CONTRIBUTING.md`, `docs/architecture.md`, `docs/README.md`.
Определены структура схем, правила версионирования (`rpk.v1.json`, `core.frame.v1.json`) и описание архитектуры.
Добавлены указания по CI/CD, тестированию и ветвлению.

---

## [2025-10-20 11:57 GMT+3]

### docs(repo_instructions): AI workflow and repo_notes

Добавлены файлы `.repo_instructions/WORKFLOW.md`, `repo_notes.md` и шаблоны (`commit_template.md`, `session_log_template.md`, `task_comment_template.md`, `detour_template.md`).
Определены правила работы ассистента, структура лога сессий и коммитов, а также формат ведения инженерных заметок.
