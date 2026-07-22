# Contributing / Правила ведения репозиториев

Это персональный набор проектов одного автора — правила ниже действуют как для будущих внешних контрибьюторов, так и как памятка самому себе / AI-ассистентам, работающим в этих репозиториях.

## Источник правил

Полная конституция и стандарты — в [github-playbook](https://github.com/Lex226/github-playbook):

- [`standards/00-constitution.md`](https://github.com/Lex226/github-playbook/blob/main/standards/00-constitution.md) — общие правила ведения любого репозитория (GitHub как источник планирования, session-снапшоты, ADR, статусная модель, labels, аудиты).
- [`standards/labels.json`](https://github.com/Lex226/github-playbook/blob/main/standards/labels.json) — единый набор меток.
- [`docs/github/`](https://github.com/Lex226/github-playbook/tree/main/docs/github) — практический cheatsheet по GitHub CLI, Issues, Labels, Milestones.

Этот файл (`.github/CONTRIBUTING.md`) применяется по умолчанию ко всем репозиториям без своего `CONTRIBUTING.md` — не дублирует содержимое `github-playbook`, только ссылается на него.

## Быстрая памятка

1. Перед началом работы — прочитать README репозитория и последний session-снапшот (если есть).
2. Спорные решения — фиксировать через ADR, а не молча в коде/документах.
3. Задачи и находки — через GitHub Issues, с метками `stage:*` и `priority:*` из единого набора.
4. Заканчивать сессию — session-снапшотом (`sessions/` или `session-log/`).
5. PR — использовать шаблон [`.github/pull_request_template.md`](pull_request_template.md).

## Шаблон нового репозитория

Для нового проекта — использовать [1c-repo-template](https://github.com/Lex226/1c-repo-template) ("Use this template" на GitHub), а не создавать структуру с нуля.
