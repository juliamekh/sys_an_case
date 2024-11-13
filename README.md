Блокировки платежей (API + БД)

Представь, что ты системный аналитик на проекте в Т-банке. В вашем продукте реализован сервис по отправке платежей юридическим лицам. Но периодически возникают ситуации, когда платежи надо приостановить, потому что клиент ненадежен (есть подозрение на мошенничество и нужно время разобраться), либо клиент предоставил не те реквизиты для перечисления и платежи отбиваются банком клиента (нужно время на выяснение верных реквизитов).

Запрос бизнеса следующий:
- нужна возможность заблокировать платежи конкретного клиента;
- нужна возможность разблокировать платежи клиента;
- нужна возможность проверить, заблокирован ли клиент;
- нужна возможность отличать блокировки мошенников от блокировок добропорядочных клиентов.
- 
Тебе надо предложить решение по реализации этого запроса бизнеса:
Подготовить спецификацию (желательно в формате OpenAPI / Swagger) endpoint’ов для реализации задач выше;
Предложить структуру хранения нужной информации в БД.
