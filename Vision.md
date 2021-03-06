#  Видение
Краткое наименование: **Crystal**

Полное наименование: **Информационная система определения пригодности воды для употребления**

## Введение
**Crystal** - информационная система, предназначенная для измерения значений параметров воды, а также отображения их и определения результата пригодности употребления анализируемой воды в мобильном приложении. Определённые системой значения параметров воды и результаты пригодности заносятся в базу данных для ведения статистики и истории замеров.

## Возможности
Система может определять значения таких параметров:
- температуру воды
- мутность воды
- кислотность воды
- минерализацию воды

Аппаратная часть:
- определение значений параметров воды
- передача значений параметров воды

Мобильное приложение:
- приём значений параметров воды
- отображение значений параметров
- отображение норм значений параметров
- определение результата рекомендации употребления воды 
- отображение результата рекомендации употребления воды
- добавление значений параметров и результатов рекомендаций в БД
- отображение истории произведённых замеров
- отображение статистики значений параметров воды
- настраиваемые push-уведомления

(настраиваемое время работы системы)?

## Рынок
### Экономические предпосылки
Вода – важный питательный элемент для всех живых организмов. Человеку необходимо употреблять воду каждый день для того, чтобы жить. Очень важно употреблять именно качественную, чистую воду, так как от этого зависит здоровье. Поэтому потребность в употреблении качественной воды остаётся актуальной.

### Тенденции 
- Употребление чистой воды
- Усиление желания следить за своим здоровьем
- Популяризация употребления чистой воды среди населения

### Область применения
Система предназначена для мест, оснащённых предполагаемым источником питьевой воды.

### Заинтересованные лица 
Заинтересованные лица | Цель высокого уровня | Проблемы, возможности и замечания | Текущие решения
--- | --- | --- | ---
Люди | Забота о своём здоровье | Непонимание о пригодности воды для питья | (Тестеры качества воды)

### Позиционирование
С точки зрения пользователя, система будет являться информатором, который может отображать значения параметров воды, пригодность воды для употребления, историю произведённх замеров, статистику значений параметров воды.

## Компоненты системы
Система включает в себя как аппаратную часть, так и программную. Аппаратным обеспечением системы является плата Arduino, bluetooth-модуль, датчик температуры, датчик мутности, датчик кислотности (pH), датчик минерализации (TDS). Программным обеспечением системы является скетч для работы микроконтроллера, а также мобильное приложение.

## Нерешённые вопросы и дальнейшие шаги разработки
1. Какие ещё датчики можно подключить?
2. Какие ещё функции можно добавить в мобильное приложение?
3. В каком виде должен быть прототип?
