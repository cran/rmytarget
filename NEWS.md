# rmytarget 2.1.8
Дата релиза: 2019-08-14
Исправлена оибка возникающая при запросе сразу всех метрик через `metrics = "all"`.

# rmytarget 2.1.7
Незначительное техническое обновление, связанное с требованиям CRAN к виньеткам.

# rmytarget 2.1.6
## Исправление ошибок
* Исправлена ошибка в функциях myTarGetAdList и myTarGetCampaignList, ранее каждый отдельный столбец имел класс list, теперь каждый столбец является вектором содержащим данные опредёлнного типа.
* Исправлена ошибка авторизации при работе с пакетом на MasOS.

# rmytarget 2.1.5
## Исправление ошибок
* Исправлена ошибка в функции `myTarGetStats`, которая возникала в случае если запрашивались данные с группировкой по рекламным кампаниям, и в аккаунте была при этом создана всего 1 рекламная кампания.

# rmytarget 2.1.4
## Исправление ошибок
* Исправлена ошибка в функции `myTarGetStats`, которая возникала в случае если запрашивались разные группы метрик в разрезе дней.

# rmytarget 2.1.3

## Документация
* В пакет добавлены две виньетки:
	* rmytarget-auth - Авторизация в MyTarget
	* rmytarget-intro - Введение в работу с пакетом rmytarget
* В пакет добавлен русскоязычный README

## Исправление ошибок
* Исправлена ошибка в функции `myTarGetStats`, которая возникала при запросе статистики в целом за выбранный период без разбивки по датам, т.е. при использовании `stat_type = "summary"`.
