# Версии, поставка, обновления
---
## Версионирование Сравнителя
Полный номер версии программы состоит из четырех частей:

- Номер редакции
- Номер подредакции
- Номер версии
- Номер сборки

При внесении исправлений без добавления нового функционала будет увеличен только **номер сборки**.

При внесении нового функционала чаще всего будет увеличен **номер версии**. Если в конфигурацию будут внесены существенные изменения или будут переработаны целые блоки фунциональности, может быть увеличен **номер подредакции**.

## Комплект поставки
Комплект поставки Сравнителя состоит из следующих файлов:

- **1Cv8.cf** - файл конфигурации Сравнителя. Может быть использован для создания информационной базы из шаблона;
- **1Cv8.cfu** - файл обновления конфигурации с предыдущих версий;
- **МастерВыгрузкиДанныхВСравнитель.epf** - дополнительная обработка, предназначенная для встраивания в целевые информационные базы при использовании некоторых сценариев работы;
- **ШаблонПодключаемойОбработкиВыгрузки.epf** - внешняя обработка для быстрого начала разработки подключаемых обработок выгрузки;
- **ШаблонПодключаемойОбработкиСравнения.epf** - внешняя обработка для быстрого начала разработки подключаемых обработок сравнения.