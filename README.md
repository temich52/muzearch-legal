# Muzearch — legal (GitHub Pages)

Статические юридические документы для Telegram-бота Muzearch.

## Публикация

1. Создайте **публичный** репозиторий `muzearch-legal` на GitHub.
2. Скопируйте содержимое этой папки в корень репозитория.
3. **Settings → Pages → Source:** branch `main`, folder `/ (root)`.
4. После деплоя URL: `https://<username>.github.io/muzearch-legal/`

## Обновление текстов

Из корня проекта Muzearch:

```bash
python scripts/export_legal_html.py
```

Затем commit + push в репозиторий `muzearch-legal`.

## URL для бота (.env)

```env
LEGAL_PRIVACY_URL=https://<username>.github.io/muzearch-legal/privacy.html
LEGAL_TERMS_URL=https://<username>.github.io/muzearch-legal/terms.html
LEGAL_CROSS_BORDER_URL=https://<username>.github.io/muzearch-legal/cross-border.html
```
