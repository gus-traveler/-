# Портфолио: инженер по тестированию

### Обо мне
Меня зовут Медведева Екатерина, я начинающий тестировщик.
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

### Навыки и технологии
Jira, qase.io, SQL, Postman, Fiddler, Swagger, Trello,
SoapUI, Android Studio, xCode, Charles, Git, Chrome DevTools.

### Проекты

##### Проект 1: тест веб-приложения для учителей от Skyeng

Что нужно было сделать:

1️⃣ сделать тест-план,

2️⃣ подготовить тестовую документацию,

3️⃣ провести тестирование,

4️⃣ написать отчет о результатах тестирования.

Как решала(-а): краткое описание решения (автореферат)

[Ссылка на проект](https://gus-traveler.atlassian.net/wiki/spaces/OT/pages/1179649/1+2)

##### Выводы (итоги): 
1️⃣ Новый функционал “Личные события” готов и рекомендован к выпуску для пользователей, так как в процессе тестирования были найдены 3 бага со средним приоритетом. Найденные баги не затрагивают критически важного функционала, дымовое тестирование пройдено успешно. UX/UI тестирование показало, что функционал удобен в использовании и интуитивно понятен пользователям.

2️⃣ При регрессионном тестировании был найден баг с высоким приоритетом, блокирующий основной функционал продукта, а именно отмена урока. KU1-4: Во вкладке расписание при отмене урока появляется ошибка 500 ОК
На основании регрессионного тестирования я считаю, что до исправления регрессионного бага выпускать продукт еще рано, так как пользователи (учителя) не смогут отменить урок при необходимости, столкнутся с проблемой в планировании уроков и разочаруются в продукте. Заказчик : компания Скайпро стремится выпускать только качественные продукты, удобные в использовании, если выпустить продукт сейчас, то это может понизить рейтинг компании и лояльность пользователей ее продуктов.

 
##### Проект 2: тестирование кабинета учителя в приложении Skyeng

Что нужно было сделать:

1️⃣ дополнить тест-план,

2️⃣ создать коллекцию в Postman,

3️⃣ провести тест-ран,

4️⃣ на основе результатов тест-рана дополнить отчет о тестировании.

Как решала(-а): краткое описание решения (автореферат)

[Ссылка на проект](https://gus-traveler.atlassian.net/wiki/spaces/OT/pages/1179649/1+2)

##### Выводы (итоги): 
1️⃣По результатам проведенного тест-рана в Postman обнаружены дефекты:  

- В тест-кейсе 8 найден баг: KU1-2: При заполнении поля описание во вкладке личное событие ограничение в 500 символов

- В тест-кейсе 9 найден баг: KU1-5: При создании личного события с некорректной датой через API система принимает данные и создает событие
 
2️⃣ Проведено тестирование API, проверены основные функции API для работы с функционалом “Личные события”,  на запросы приходит код ответа 200, события возможно создать, отредактировать и удалить. Все функции работают в соответствии с документацией, зафиксированы найденные дефекты.

3️⃣Получилось написать 2 тест-кейса, которые возможно проверить через API, но невозможно проверить через интерфейс: 
- 9 “Создание личного события с некорректной датой”
- 10 "Создание личного события с неустановленной датой"

Найден дефект в тест-кейсе  9 “Создание личного события с некорректной датой API”, в котором найден баг: KU1-5: При создании личного события с некорректной датой через API система принимает данные и создает событие
 

### Контактная информация 
**Email:** <katerinamedvedeva@mail.ru>

LinkedIn: 

Личный сайт: 
