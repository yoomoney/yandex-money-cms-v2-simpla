# yoomoney-cms-simpla

Модуль оплаты yoomoney-cms-simpla необходим для интеграции с сервисом [ЮKassa](https://yookassa.ru/) на базе CMS SimplaCMS. 

Существует два платежных сценария: с выбором способа оплаты на сайте магазина и на стороне ЮKassa. 

> **Выбор способа оплаты на сайте магазина** 
> В этом случае в настройках модуля отмечаются все способы оплаты, доступные этому магазину и плательщик выбирает нужный ему метод из списка на сайте магазина. Этот сценарий доступен всем магазинам по умолчанию.

> **Выбор способа оплаты на стороне ЮKassa**
> Все доступные магазину способы появятся на стороне ЮKassa сами. Новые способы оплаты будут добавляться автоматически. 

Доступные платежные методы, если вы работаете как юридическое лицо:
* **Банковские карты** -  Visa (включая Electron), MasterCard и Maestro любого банка мира
* **Электронные деньги** - ЮMoney, WebMoney и QIWI Wallet
* **Наличные** - [Более 170 тысяч пунктов](https://yoomoney.ru/doc.xml?id=526209) оплаты по России
* **Баланс телефона** - Билайн, МегаФон и МТС
* **Интернет банкинг** - Альфа-Клик, Сбербанк Онлайн, MasterPass и Промсвязьбанк
* **Кредитование** - Доверительный платеж (Куппи.ру)

### Поддержка передачи данных чека
Если вы настраивали отправку чеков в налоговую через партнеров ЮKassa (по 54-ФЗ), в настройках модуля надо включить отправку данных для чека.
[Помощь ЮKassa: отправка чеков по 54-ФЗ](https://yookassa.ru/docs/support/payments/tax-sync)

### Установка модуля
Для установки данного модуля необходимо скопировать каталог `payment` из [архива](https://github.com/yoomoney/cms-simpla/archive/master.zip) в корень Вашего сайта с заменой файлов на новые.

Пожалуйста, обязательно делайте бекапы!

### Лицензионный договор.
Любое использование Вами программы означает полное и безоговорочное принятие Вами условий лицензионного договора, размещенного по адресу https://yoomoney.ru/doc.xml?id=527132 (далее – «Лицензионный договор»). 
Если Вы не принимаете условия Лицензионного договора в полном объёме, Вы не имеете права использовать программу в каких-либо целях.

### Нашли ошибку или у вас есть предложение по улучшению модуля?
Пишите нам cms@yoomoney.ru
При обращении необходимо:
* Указать наименование CMS и компонента магазина, а также их версии
* Указать версию платежного модуля (доступна на странице настроек модуля)
* Описать проблему или предложение
* Приложить снимок экрана (для большей информативности)