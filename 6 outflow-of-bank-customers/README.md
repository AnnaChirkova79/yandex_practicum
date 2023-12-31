**Описание проекта:**

Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.
Необходимо построить модель с предельно большим значением F1-меры и довести метрику до 0.59. Проверяем F-1 на тестовой выборке. Дополнительно необходимо измерить AUC-ROC, сравнивая её значение с F1-мерой.

**Выводы:**

Проведена предобработка данных и исследовательский анализ. В процессе исследования данных:
1.	Признаки не сильно коррелируются с целевым признаком. Линейная зависимость не выявлена.
2.	Клиенты в возрасте от 39 до 52 уходят чаще. Однако прямой зависимостью это назвать нельзя, так как клиентов в данном возрасте больше, чем в других возрастных группах.
3.	Клиенты, у которых всего 1 или два продукта банка уходят чаще.
4.	Зависимость оттока от наличия кредитной карты не выявлена.
5.	Неактивные клиенты уходят чаще.
6.	Категориальные признаки переведены в дамми переменные.


**Навыки и инструменты:**
Python, Pandas, Matplotlib, NumPy, SciPy, предобработка данных, работа с дубликатами, пропусками данных, работа с типами данных, 
абота с выбросами и отклонениями,  работа с дисбалансом в данных, категоризация данных, визуализация данных, проверка статистических гипотез,
работа с моделями решающее дерево, случайный лес, логистическая регрессия.

**Статус проекта:** Завершен.
  

