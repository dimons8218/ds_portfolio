# Выявление закономерностей, определяющих коммерческую успешность игры

## Описание проекта

Я работаю в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников мне доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).

Передо мной данные до 2016 года, а я планирую кампанию на 2017-й. Мне необходимо отработать принцип работы с данными. Неважно, прогнозирую ли я продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.

## Данные

Данные содержат следующие признаки:
- название игры;
- платформа;
- год выпуска;
- жанр игры;
- продажи в Северной Америке (миллионы проданных копий);
- продажи в Европе (миллионы проданных копий);
- продажи в Японии (миллионы проданных копий);
- продажи в других странах (миллионы проданных копий);
- оценка критиков (максимум 100);
- оценка пользователей (максимум 10);
- рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## Задача исследования

Выявить определяющие успешность игры закономерности, которые позволят сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Используемые библиотеки

*pandas, scipy, matplotlib, seaborn*

## Выводы

Мной были выявлены следующие закономерности, определяющие успешность игры:
- набирают объёмы продаж игр на платформы PS4 и XOne, которые также входят в лидеры по количеству миллионов проданных копий игр с 2012 года;
- положительные отзывы критиков (с оценкой более 60) играют важную роль в объёмах продаж игр;
- наиболее популярны игры в жанрах Action и Sports, однако стабильно наибольшую прибыль медианно приносят игры в жанрах Shooter, Sports и Platform;
- во всех регионах высокой популярностью пользуются игры для всех (E).
