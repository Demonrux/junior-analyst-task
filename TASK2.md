# Задание 2: проектирование API
## Описание:
Интернет-магазин "Петрушка Зеленая" преуспевает, расширяется и в мобильном приложении решили создать новый экран, который будет отображать магазины партнеро

## Запрос

**GET** ` https://host/api/partner-stores`

Получение списка магазинов партнёров с примерным временем доставки.

## Стурктура ответа
```json
{
  "total": 2,
  "stores": [
    {
      "id": 101,
      "name": "Продуктовый рай",
      "image": "https://cdn.example.com/logos/101.png",
      "delivery_time": "15–25 мин",
      "url": "https://produktiray.ru/magazin"
    },
    {
      "id": 102,
      "name": "ТехноМир",
      "image": "https://cdn.example.com/logos/102.png",
      "delivery_time": "30–45 мин",
      "url": "https://tehnomir.com/partner"
    }
  ]
}
```
