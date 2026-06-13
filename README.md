# Muzearch — юридические документы

Официальные тексты для Telegram-бота [Muzearch](https://temich52.github.io/muzearch-legal/): политика конфиденциальности, пользовательское соглашение и согласие на трансграничную передачу данных для AI-функций.

**Сайт:** [https://temich52.github.io/muzearch-legal/](https://temich52.github.io/muzearch-legal/)

## Документы

| Файл | Описание |
|------|----------|
| [privacy.html](privacy.html) | Политика конфиденциальности (152-ФЗ) |
| [terms.html](terms.html) | Пользовательское соглашение |
| [cross-border.html](cross-border.html) | Согласие на передачу данных провайдерам AI |

Текущая версия: **6** (с 14 июня 2026).

## Контакты оператора

- Telegram: [@piece0l](https://t.me/piece0l)
- Email: [artemkliuev@gmail.com](mailto:artemkliuev@gmail.com)

## Обновление

Исходные тексты хранятся в репозитории [muzearch](https://github.com/temich52/muzearch) (`views/legal.py`).
После правок:

```bash
python scripts/export_legal_html.py
cd muzearch-legal && git add -A && git commit -m "Update legal pages" && git push
```

## GitHub Pages

Репозиторий публикуется через **Settings → Pages → branch `main`**, folder `/ (root)`.
