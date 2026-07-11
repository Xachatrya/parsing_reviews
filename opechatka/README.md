# О! печатка — материалы

Анализ бизнеса и готовые карточки товаров по данным [Яндекс.Карт](https://yandex.ru/maps/-/CTBfVV3z).

## Содержание

| Файл | Назначение |
|---|---|
| [ANALIZ_BIZNESA.md](./ANALIZ_BIZNESA.md) | SWOT, сегменты, отзывы, рекомендации |
| [cards/KARTOCHKI.md](./cards/KARTOCHKI.md) | Тексты карточек для публикации |
| [cards/tovary.json](./cards/tovary.json) | Структурированные данные (19 услуг + 4 пакета) |
| [cards/index.html](./cards/index.html) | Визуальная витрина карточек |

## Как открыть витрину

```bash
cd opechatka/cards && python3 -m http.server 8080
```

Затем откройте `http://localhost:8080`.
