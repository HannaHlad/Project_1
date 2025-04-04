# Project_1

 В данном проекте я проведу эксперимент. Для этого буду применять метод A/B–тестирования. В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. В данном эксперименте мне необходимо проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новую механику оплаты на всех пользователей.

**В качестве входных данных вы имеете 4 csv-файла:**

 - **groups.csv** – файл с информацией о принадлежности пользователя к контрольной или экспериментальной группе (А – контроль, B – целевая группа) 
 - **groups_add.csv** – дополнительный файл с пользователями, который нам прислали спустя 2 дня после передачи данных
 - **active_studs.csv** – файл с информацией о пользователях, которые зашли на платформу в дни проведения эксперимента. 
 - **checks.csv** – файл с информацией об оплатах пользователей в дни проведения эксперимента.


**В ходе данного проекта:**
- Протестировала гипотезу по новой механике оплаты услуг на сайте
- Проверила нормальность распределения групп
- Подобрала метод для проведения A/B теста
- Нарисовала графики
- Рассчитала метрики 
- Сделала выводы по данным полученным в ходе исследования


**Выводы:**
-  Мы имеем статистически значимую разницу конверсий в покупку. Контрольная группа проявила себя лучше в этих показателях.

- Статистически значимых значений мы не имеем для всех пользователей присутствующих на платформе, но у нас подтвердились различия  в чеках пользователей совершивших оплату. В этих значения тестовая группа показала себя лучше.

- Дать однозначный ответ стоит ли выкатывать обновления на всех пользователей на данном этапе невозможно. Необходимо получить дополнительную информацию по целям АВ теста, изменениям и тд.
Я бы еще посмотрела на путь клиента. на каком этапе тестовая группа не доходила до оплаты. Возможно, новая механика оплаты некорректно срабатывала на каких-то платформах или операционных системах и тд.


