# api_python

# Проект «Мой статический сайт»

## Что сделано

* Создана собственная тема MkDocs на основе Tailwind CSS.
* Добавлен кастомный header, footer и стилизованная главная страница.
* Весь CSS проходит через PostCSS, минифицируется и валидируется.
* HTML‑файлы проверяются через `htmlhint`.
* Автоматический билд и деплой на GitHub Pages реализован в GitHub Actions.

## Как запустить локально

```bash
npm ci
npm run build:assets
pip install mkdocs
mkdocs serve
