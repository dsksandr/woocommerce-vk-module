# WooCommerce x VKontakte

![WooCommerce x VKontakte](https://sun4.userapi.com/sun4-12/s/v1/ig2/kAK4PePlk2VcoFj7kV5ra202sAYIPbW12hj1QrPUVpPuj-nkhzVJLE5qCIPpapp4XQR_El4KofwOR9guc-47-JLa.jpg?size=807x547&quality=96&type=album)

- Загрузка каталога товаров WordPress => магазин ВКонтакте
- Загрузка каталога товаров магазин ВКонтакте => WordPress
- Получение заказов (создание/изменение) магазин ВКонтакте => WordPress
- Передача изменений по статусу заказа WordPress => магазин ВКонтакте

[Инструкция по подключению и настройке модуля интеграции ВКонтакте — WordPress](https://vk.com/@business-instrukciya-po-podklucheniu-i-nastroike-modulya-integracii-v)

## composer.json

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/dsksandr/woocommerce-vk-module.git"
        }
    ],
    "require": {
        "dsksandr/woocommerce-vk-module": "dev-main"
    }
}
```
