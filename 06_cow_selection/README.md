# Выбор коров с определёнными характеристиками для фермера

## Описание проекта

Вы работаете в IT-компании, которая выполняет на заказ проекты по машинному обучению. К вам обратился фермер, владелец молочного хозяйства «Вольный луг». Он хочет купить бурёнок, чтобы расширить поголовье стада коров. Для этого он заключил выгодный контракт с ассоциацией пастбищ «ЭкоФерма». Условия позволяют фермеру очень тщательно отобрать коров. Он определяет качество молока по строгой методике, и при этом ему нужно выполнять свой план развития молочного хозяйства. Фермер хочет, чтобы каждая бурёнка давала не менее 6000 килограммов молока в год, а её надой был вкусным — строго по его критериям, ничуть не хуже. А продавцы и технологи так и норовят приукрасить своих коровок! «ЭкоФерма» готова предоставить подробные данные о своих коровах.

## Данные

Данные состоят из трёх датасетов:
- данные о стаде фермера на текущий момент (характеристики коровы, характеристики корма, характеристика пастбища, характеристики молока);
- имя папы каждой коровы в стаде фермера;
- данные о коровах «ЭкоФермы», которых фермер хочет изучить перед покупкой.

## Задача исследования

Разработать модель машинного обучения, которая поможет фермеру управлять рисками и принимать объективное решение о покупке.  Для этого необходимо создать две прогнозные модели для отбора бурёнок в поголовье:
- Первая будет прогнозировать возможный удой коровы (целевой признак Удой);
- Вторая — рассчитывать вероятность получить вкусное молоко от коровы (целевой признак Вкус молока). С помощью модели нужно отобрать коров по двум критериям:
средний удой за год — не менее 6000 килограммов;
молоко должно быть вкусным.

## Используемые библиотеки
*pandas, numpy, scipy, matplotlib, seaborn, sklearn, phik*