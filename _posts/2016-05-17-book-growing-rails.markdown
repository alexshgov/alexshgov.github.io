---
layout: 'post'
title: 'Книги: Growing Rails applications in practice'
date: '2016-05-17'
---

![Image](https://s3.amazonaws.com/titlepages.leanpub.com/growing-rails/hero?1467710010)

Книга не нова, но добрался я до нее только сейчас.

Пожалуй, это даже к лучшему, т.к. некоторые вещи, описанные в ней, становятся понятны только в том случае, если на самом себе почувствовал последствия тех или иных архитектурных решений.

Краткий вывод — прочитать ее стоит если и не очень внимательно, то вскользь точно. Но, считаю, что читать ее людям, которые пришли в мир разработки на Rails и успели сделать один лишь блог по туториалу Хартла, рано. Стоит сделать несколько своих велосипедов, поставить себе такие задачи, которые заставят изменить логику проекта, и после прочувствовать, насколько легко воплотить такие изменения в жизнь.

Простой пример: приходит заказчик и говорит: “Дорогой разработчик, мне нужна регистрация пользователей в моем магазине, с такими-то полями, и такими-то….”. Ок, делаем. Модель User, миграции, валидации, контроллер, формочка. Все работает, все довольны.

Заказчик звонит: “Вау! Разработчик, Вы такой молодец, так быстро все сделали! (Он же не знает, что мы просто devise подключили) А давай-ка мы теперь сделаем в нашем магазине не только простых пользователей, но и администраторов, а также владельцев магазинов. Формы у этих троих будут различаться так-то и так-то и бла-бла…..”.
И разработчик думает: “сделать еще две различные модели для этих сущностей будет глупо”. И делает он какую-нибудь модель с ролями, и навешивает кастомные валидации с кучей :if, которые проверяют, а какой же там параметр роли пришел нам из формы?
Не стоит говорить, что это очень некрасиво. Да и тестировать такое дело становится сложно.

Эта книга если не покажет полностью, то как минимум натолкнет на решения, которые помогут разрешить такие и подобные моменты при разработке.
