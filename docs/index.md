# DevOps Operations Handbook

Учебный сайт документации, собираемый из Markdown и публикуемый через GitHub Actions.

**Версия: 2.** Этот маркер используется при исследовании неудачного выпуска.

План восстановления: [recovery.md](recovery.md).

## Контур поставки

1. Изменение предлагается через Pull Request.
2. Pylint проверяет Python-код.
3. После слияния в `main` MkDocs собирает статический сайт.
4. GitHub Pages публикует артефакт сборки.

Адрес будущего сайта: `https://mist1qu3x.github.io/devops-docs/`.
