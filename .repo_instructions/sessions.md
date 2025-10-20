<!-- markdownlint-configure-file {"MD041": false} -->

## [2025-10-15]

**Начало:** 14:00 GMT+3
**Окончание:** 15:30 GMT+3

### Выполнено

- Определена структура репозитория `cd-schemas` — центрального хранилища контрактов данных для системы Coffee Digital Reborn.
- Созданы каталоги:
  - `jsonschema/manifest/` — схемы RPK и firmware;
  - `jsonschema/telemetry/` — схемы кадров телеметрии (core, pump и др.);
  - `docs/` — архитектура и описание структуры проекта.
- Подготовлены пустые схемы-заглушки (`{}`) для начальной валидации.
- Добавлены и настроены инструменты форматирования и проверки (`pre-commit`, `markdownlint`, `prettier`).
- Сформированы основные файлы документации: `README.md`, `CONTRIBUTING.md`, `docs/architecture.md`, `docs/README.md`.
- Добавлены `.repo_instructions/WORKFLOW.md`, `repo_notes.md` и шаблоны (`commit_template.md`, `session_log_template.md`, `task_comment_template.md`, `detour_template.md`).
- Определены правила ведения инженерных заметок и логирования сессий.
- Установлена структура версионирования схем (`rpk.v1.json`, `core.frame.v1.json`) и принципы обратной совместимости.

### Коммиты

- `docs: Create README.md`
- `chore: workspace setup, formatting & linting, gitignore`
- `chore: directory structure`
- `docs: Определение структуры документации`
- `docs(repo_instructions): AI workflow and repo_notes`

### Незавершённые задачи

- Заполнение JSON Schema фактическими описаниями объектов (`manifest`, `telemetry`, `mqtt`).
- Добавление OpenAPI-спецификаций для SaaS и сервисов Headunit.
- Настройка тестов валидации схем (JSON Schema validation, pytest).
- Подготовка автоматической сборки схем и генерации документации.
- Включение репозитория `cd-schemas` как подмодуля в другие компоненты.

### Следующие шаги

- Реализовать генерацию схем на основе существующих структур данных ESP/Headunit.
- Добавить OpenAPI для SaaS и документировать в `docs/architecture.md`.
- Подключить проверку схем через CI-пайплайн.
- Оформить README с примерами валидации и использованием схем в других проектах.
