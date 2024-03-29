###### <u>ПОРТФОЛИО: ИНЖЕНЕР ПО ТЕСТИРОВАНИЮ</u>

### ОБО МНЕ:

Привет! Меня зовут Марго. Я - начинающий специалист по тестированию. Здесь вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

#### НАВЫКИ И ТЕХНОЛОГИИ:

 - `Jira `
   [https://youtu.be/1MfBwrvlciQ]
   [https://youtu.be/ufacWyi24w4]
- `qase.io`,
  [https://youtu.be/xT9Dxk6vSso]
  [https://youtu.be/dydaysHd4BQ]
- `Postman` `Swagger`, `Trello`,
`SoapUI`, `xCode`, `Charles`, `Git`, `Chrome DevTools`, `SQL`




**ПРОЕКТЫ**

Проект 1: Тест веб-приложения для учителей от Skyeng

Что нужно было сделать:

1.Провести функциональное тестирование 
2.Провести тестирование API
Как решала: 
1. При помощи декомпозиции сайта поделила продукт на модули и провела - Функциональное тестирование со стороны бэкенда, smoke-тестирование, приемочное тестирование, регрессионное тестирование
2. С помощью приложенных Свагеров провела тестирование API через Postman

Ссылка на проект: [https://www.notion.so/Course-Work-1-2-4fe5bee018254e8bbef46155d5ae6e5d?pvs=4]

**ВЫВОДЫ (ИТОГИ):**

Итог №1 
- При проведении тестирования заданного функционала были выявлены минорные баги, которые не будут мешать Стейкхолдерам дабавлять личные события.
- Также был выявлен блокирующий баг, как “ Личное событие не создается в прошлом времени при создании и редактировании”. Эта часть основного функционала пользователя, и запуск продукта, не исправив этот баг приведет к краху приложения.
- В том числе при проведении регрессионного тестирования было выявлено 2 блокирующих бага одной функции “Промежуток времени недоступен к применению в функционале уроков при создании и редактировании”, соответственно старый функционал был поврежден при введении нового. Запуск продукта, не исправив этот баг приведет к краху приложения.
- Остальные баги класса S2 и ниже также влияют на общую картину и работу сайта.
Итог №2 В результате тестирования API, было найдено 3 бага:

1. При превышении допустимого количества символов в заголовке и описания события, отображается статус “200”, но в теле ответа отображается ошибка, что является минорным багом
2. При вводе невалидного времени события, отображается статус “200”, но в теле ответа отображается ошибка, что является минорным багом


**Рекомендации:**

ФРОНТЕНД:

Сайт не готов к запуску, а если он уже запущен, немедленно исправить баги S1.

Все вышеперечисленные критерии попадают под критерий “Приостановки тестирования”. пока самый главный блокирующий баг не будет исправлен :)

БЭКЕНД:

Найденные Баги - минорные, что попадает под критерий “Продолжение тестирования”


