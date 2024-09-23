 | № **п/п** | **Параметр** | **Кратность** | **Тип** | **Описание** |
   | --- | --- | --- | --- | --- |
   |  | Parameter.name | 1\..1 | string | «referenceLocation» |
   |  | Parameter.valueReference | 1\..1 | Reference | Ссылка на Location |
   |  | Parameter.name | 1\..1 | string | «referenceOrganization» |
   |  | Parameter.valueReference | 1\..1 | Reference | Ссылка на Organization (целевая МО) |
   |  | Parameter.name | 1\..1 | string | «referencePatient» |
   |  | Parameter.valueReference | 1\..1 | Reference | Ссылка на Patient |
   |  | Parameter.name | 1\..1 | string | «occurrencePeriod» |
   |  | Parameter.valuePeriod | 0\..1 | Period | Временной интервал удобного времени ожидания врача |
   |  | start | 1\..1 | dateTime | Дата и время начала временного интервала |
   |  | end | 1\..1 | dateTime | Дата и время окончания временного интервала |
   |  | Parameter.name | 1\..1 | string | «reason» |
   |  | Parameter.valueString | 1\..1 | string | Причина вызова врача на дом (например, «Высокая температура, кашель») |
