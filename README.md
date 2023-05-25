# php-bot-feedback
Примитивный бот обратной связи на PHP без использования библиотек.

Чтобы бот работал после создания его через @BotFather нужно поставить «Webhook» чтобы все сообщения из Telegram приходили на PHP скрипт (https://example.com/bot.php). Для этого нужно пройти по ссылке в которой подставлены полученный токен из @BotFather и адрес скрипта.

`https://api.telegram.org/bot<TOKEN>/setWebhook?url=https://example.com/bot.php`

В ответе будет что-то типо того

```json
{"ok":true,"result":true,"description":"Webhook was set"}
```

Рабочий пример бота https://t.me/zchk0_bot
