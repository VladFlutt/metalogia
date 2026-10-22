# Студия Металогия

Статический лендинг студии внедрения ИИ. Деплой на Vercel без сборки.

## Как добавить кейс

1. Положите PDF в папку `cases/`.
2. Добавьте запись в JSON внутри `<script id="cases-data">` в `index.html`: `title`, `industry`, `year`, `result`, `file` (`/cases/имя.pdf`), `size` в байтах и `kind` (`business` или `social`).
