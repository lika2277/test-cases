# Тестирование интерфейса

Параметры:

* подход к тестированию функционала: "черный ящик"
* тип тестирования: "функиональное" - "исследовательское"
* система управления тесткейсами: github
* система управления проектом: github
* ОС: Windows, версия 11
* браузер: Google Chrome, версия 115.0.5790.110

# Тест-кейс

## Просмотр страницы [https://math.uchi.ru/fr](https://math.uchi.ru/fr)

### Таблица 1. Прокрутка сайта от начала до низа страницы [https://math.uchi.ru/fr](https://math.uchi.ru/fr)

| № | Шаг |  Изображения шага | Ожидаемый результат | Изображения ожидаемого результата |
| --- | --- | --- | --- | --- |
| 1 | Прокрутка сайта от начала до конца страцы [https://math.uchi.ru/fr](https://math.uchi.ru/fr) | ![Начальная страница сайта](../screen_uchi/T_1.png) | Прокрутка сайта проходит от начала до конца страницы | ![Конец страницы](../screen_uchi/Т_2.png) |

# Чек-листы

## Просмотр страницы [https://math.uchi.ru/fr](https://math.uchi.ru/fr)



| № | Проверка | Резулььтат | Коментарии |
| --- | --- | --- | --- |
| 1 | Прокрутка сайта от начала до конца страцы [https://math.uchi.ru/fr](https://math.uchi.ru/fr) | Full | В конце страницы по футером остался текст ![Конец страницы](../screen_uchi/Т_3.png)  |


# Баг
## Просмотр страницы [https://math.uchi.ru/fr](https://math.uchi.ru/fr)

| --- | --- |
| --- | --- |
| Summary | При тестировании прокрутки сайта до конца страница под футором остался текст который следует убрать | 
| Project | Просмотр страницы [https://math.uchi.ru/fr](https://math.uchi.ru/fr) |
| Component | Прокрутка сайта от начала до конца страцы [https://math.uchi.ru/fr](https://math.uchi.ru/fr) |
| Version | ОС: Windows, версия 11; браузер: Google Chrome, версия 115.0.5790.110 |
| Severity | S3 (trivial) |
| Preority | P1 (High) |
| Status| New |
| Author| Бубнова Лилиана |
| Assigned to | Разробочик Uchi |
| Description | Прокрутка страницы [https://math.uchi.ru/fr](https://math.uchi.ru/fr); ОС: Windows, версия 11; браузер: Google Chrome, версия 115.0.5790.110; https://vscode.dev/github/lika2277/test-cases/blob/main/Avito/Login/login-web.md#L51;  При тестировании прокрутки сайта до конца страница под футором был вявлен текст который нужно убрать |
| Attachment| ![Конец страницы](../screen_uchi/Т_3.png) |