## Проект по увеличению выручки для интернет-магазина

В предстоящем проекте наша глобальная задача - найти оптимальный способ увеличения выручки интернет-магазина. У нас есть список гипотез, которые предоставил отдел маркетинга. Мы приоритизируем гипотезы согласно фреймворкам RICE и ICE, а затем проведем A/B тест самой приоритетной гипотезы. В процессе проведения А/В тестирования мы проведем стандартные шаги анализа получаемых данных:

1) Оценим кумулятивные данные (чек, выручка, конверсия) и построим необходимые графики;
2) Определим абнормальные данные (слишком большой чек или слишком большое количество заказов);
3) Рассчитаем стастистическую значимость различий по всем данным и по данным без аномалий;
4) Сделаем выводы на основе полученных данных;
5) Примем решение о продолжении или прекращении A/B теста. 

Для проведения анализа мы используем датасет с информацией о гипотезах, предложенных отделом маркетинга, и их оценками; датасет с данными о совершенных заказах (номер транзакции, идентификатор пользователя, сумма, время заказа, группа тестирования, к которой принадлежит пользователь); датасет с информацией о группах a/b тестирования.

Краткие выводы по проекту: гипотеза о том, что добавление формы подписки на всех основных страницах, принесет компании выгоду, не подтвердилась.

A/B-тест можно остановить.

В проекте мы использовали библиотеки pandas, numpy, seaborn, matplotlib, scipy.
