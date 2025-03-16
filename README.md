# Проект по анализу ...

## Структура наших датасетов:
1. **Quality of life** - наш основной датасет.

   Изначально в нем представлено 136 стран, каждой из которых присвоен рейтинг по 100-бальной шкале по следующим показателям:
   
   1) **Стабильность** - политическая и экономическая стабильность
   2) Права - правовая система государства, ее прозрачность и справедливость, права человека, свобода слова
   3) Здоровье - качество системы здравоохранения
   4) Безопасность - отражает уровень преступности, качество защиты граждан силовыми структурами от преступлений
   5) Климат - под ним стоит подразумевать экологическую обстановку в стране
   6) Стоимость жизни
   7) Привлекательность страны для эмиграции

   Датасет взят со следующего ресурса: https://www.worlddata.info/quality-of-life.php(переделать на гиперссылку). Там можно подробнее почитать про методику оценки каждого из показателей.

   На взгляд нашей команды, каждый из этих показателей по своему важен и влияет на продолжительность жизни, поэтому мы решили исключить умножение каждого из параметров на определенный коэффициент для подсчета итоговой оценки и присваивание ранга стране по нему, так как это не совсем объективно.

2. Life expectancy - в нем представлена средняя продолжительность жизни по странам и годам. Мы из него возьмем последний доступный год для каждой страны(в основном это будет 2021, самый ранний вариант - 2019).
3. Inflation - в нем представлена инфляция по странам и годам. Возьмем инфляцию за 2021 год.
4. GDP - в нем представлен ВВП по странам и годам. Возьмем ВВП за 2021 год.
5. Gini - индекс Джини по странам и годам. Он лежит в пределах от 0 до 100 и отражает уровень неравенства в стране(выше показатель - выше неравенство)
6. Education - процент людей по странам, имеющих хотя бы базовое образование.

## Выводы

