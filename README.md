# mts_books_database
В этом проекте анализирую датасет MTS Library. Для анализа создал в DBeaver базу данных на PostgreSQL. Собранные данных визуализировал в power bi. 
МТС Библиотека - приложение для чтения электронных книг, прессы и прослушивания аудиокниг, доступно для абонентов всех мобильных операторов, продукт экосистемы МТС.
В представленном датасете собраны данные по пользователям и книгам, а также по их взаимодействиям (прочтение книги пользователем) из сервиса МТС Библиотека. Данные по чтению пользователями книг собраны за 2 два года, с 01-01-2018 по 31-12-2019 включительно, и разбавлены случайным шумом. ID пользователей и книг анонимизированы.
Статистика по датасету:
150к пользователей
60к книг
1.5м взаимодействий
для 285к из них известны рейтинги


Задачи и методы формирования отчетов:

1) Анализ популярности жанров среди различных возрастных групп: Этот отчет помогает бизнесу понять, какие жанры книг предпочитают разные возрастные группы, что позволяет адаптировать рекомендации и маркетинговые кампании. Расчеты выполнены путем подсчета количества уникальных пользователей по возрастным категориям для каждого жанра.
2) Профиль активных пользователей: Отчет позволяет определить основные характеристики наиболее активных пользователей, такие как возраст и пол, что помогает в разработке целевых маркетинговых стратегий. Расчеты выполнены на основе количества взаимодействий пользователей с книгами.
3) Рейтинг авторов по возрастным группам: Анализ популярности авторов среди различных возрастных групп помогает выявить предпочтения пользователей и направлять рекламные усилия на целевые аудитории. Расчеты проведены на основе количества уникальных пользователей, взаимодействующих с книгами различных авторов.
4) Корреляция между возрастом и рейтингом книг: Этот отчет показывает, как возраст пользователей влияет на выставляемые ими рейтинги, что помогает в понимании возрастных предпочтений и адаптации контента. Расчеты выполнены путем анализа среднего рейтинга книг по возрастным категориям пользователей.
5) Динамика чтения книг по годам публикации: Отчет показывает, книги какого года выпуска наиболее популярны среди пользователей, что позволяет выявить тенденции и направить усилия на продвижение книг определенных периодов. Расчеты проведены на основе количества взаимодействий пользователей с книгами разных лет издания.
6) Рейтинг книг по жанрам и их авторам: Определение лучших книг и жанров на основе пользовательских рейтингов и прогресса чтения помогает улучшить рекомендации и повысить удовлетворенность пользователей. Расчеты включают анализ среднего рейтинга и прогресса чтения для каждой книги и жанра.
7) Паттерны чтения пользователей: Анализ временных паттернов чтения помогает понять, в какое время года или в какие дни недели пользователи чаще всего читают, что полезно для планирования рекламных кампаний и предложений. Расчеты основаны на количестве пользователей, читающих в различные дни.
8) Влияние начала чтения на завершение книги: Исследование зависимости между датой начала чтения и процентом завершения книги помогает выявить, влияет ли сезон на вероятность завершения книги, что может помочь в оптимизации рекомендаций. Расчеты проведены на основе анализа прогресса чтения и количества завершенных книг по сезонам.
9) Профиль пользователей с наивысшими рейтингами: Отчет позволяет определить характеристики пользователей, которые ставят наивысшие оценки книгам, что помогает в разработке целевых предложений и улучшении пользовательского опыта. Расчеты выполнены путем анализа возраста и пола пользователей, выставляющих максимальные оценки.
10) Анализ книг с наименьшим прогрессом чтения: Определение книг, которые пользователи чаще всего начинают, но не заканчивают, помогает выявить проблемы в контенте или рекомендации, что способствует улучшению качества сервиса. Расчеты выполнены на основе анализа прогресса чтения и количества начатых, но не завершенных книг.
