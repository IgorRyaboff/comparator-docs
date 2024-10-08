# Передача выгрузок Сравнителю целевыми базами
---
> ***Внимание!** Для применения данного сценария требуется установить [Мастер выгрузки данных](wizard-install.md) в каждую из целевых информационных баз.*

> ***Внимание!** Для работы этого сценария требуется, чтобы обе целевые базы работали в операционной системе Windows, а в системе была зарегистрирована COM-компонента V83.COMConnector той же версии платформы, на которой работают целевые ИБ и ИБ Сравнителя. Поддержка подключения к Сравнителю через Web-сервис планируется в будущих версиях конфигурации.*

Данный сценарий срабатывает исключительно по инициативе целевых информационных баз. В каждой из целевых баз настраивается:

- Строка соединения и данные пользователя **информационной базы Сравнителя**;
- Расписание команды "**Выгрузить данные в Сравнитель**".

Помимо данных информационной базы Сравнителя, в настройках Мастера выгрузки также требуется указать:

- **Идентификатор правила сравнения** - его можно получить в карточке правила сравнения в Сравнителе;
- **Ключ пары ИБ** - позволяет идентифицировать эту пару ИБ и отличить ее от других пар ИБ, сравниваемых по этому же правилу сравнения. Должен быть **одинаковым** в настройках обеих целевых баз, а также **не повторяться** в других парах информационных баз, которые передают данные в ту же информационную базу Сравнителя и используют то же правило сравнения.