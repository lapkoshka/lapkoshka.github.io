### Запуск

Демо URL:
https://lapkoshka.github.io/?transactionId=01992563-769f-73d6-827f-f938714737d7
где transactionId индентификатор транзакции из
- /api/v1/subscriptions/start
= /api/v1/pay/start


Работает на тестовом стенде, URL фрейма - https://payment-widget.asapcashier-dev.com/?transactionId=01992563-769f-73d6-827f-f938714737d7

Для разделения методов указать параметр
`paymentMethod: 'applepay' | 'card'`

ApplePay фрейм:
https://payment-widget.asapcashier-dev.com/?transactionId=01992563-769f-73d6-827f-f938714737d7&paymentMethod=applepay

Bank card фрейм:
https://payment-widget.asapcashier-dev.com/?transactionId=01992563-769f-73d6-827f-f938714737d7&paymentMethod=card
