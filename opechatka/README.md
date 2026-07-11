# О! печатка — материалы

Анализ бизнеса и готовые карточки товаров по данным [Яндекс.Карт](https://yandex.ru/maps/-/CTBfVV3z).

## Полноценный сайт (главное)

Откройте файл:

**[`site/index.html`](./site/index.html)**

В нём: герой-экран, анализ, SWOT, сегменты, 19 карточек услуг с фильтрами, пакеты и контакты.

### Способ 1 — скачать и открыть на компьютере

1. Скачайте ZIP ветки:  
   https://github.com/Xachatrya/parsing_reviews/archive/refs/heads/cursor/opechatka-business-analysis-0d9f.zip
2. Распакуйте архив.
3. Зайдите в папку `opechatka/site/`.
4. Дважды кликните `index.html` — сайт откроется в браузере.

### Способ 2 — через локальный сервер

```bash
cd opechatka/site && python3 -m http.server 8080
```

Откройте в браузере: http://localhost:8080

## Содержание

| Файл | Назначение |
|---|---|
| [site/index.html](./site/index.html) | **Полноценный сайт** — вся работа в одном месте |
| [ANALIZ_BIZNESA.md](./ANALIZ_BIZNESA.md) | SWOT, сегменты, отзывы, рекомендации |
| [cards/KARTOCHKI.md](./cards/KARTOCHKI.md) | Тексты карточек для публикации |
| [cards/tovary.json](./cards/tovary.json) | Структурированные данные (19 услуг + 4 пакета) |
| [cards/index.html](./cards/index.html) | Отдельная витрина только карточек |