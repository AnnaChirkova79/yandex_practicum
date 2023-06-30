**Описание проекта**

Необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию,
с целью защиты данных клиентов страховой компании. Обосновали корректность работы такого метода.
Данные нужно защитить так, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. 

**Выводы:**

1.	Провели исследование датафрейма в рамках предобработки данных.
2.	Создали случайную обратимую матрицу.
3.	Далее признаки умножили на рандомную обратимую матрицу.
4.	Потом провели обучение модели и посмотрели изменится ли r2, если модель обучать на преобразованных признаках.
5.	Проведенное сравнение качества моделей до преобразования и на преобразованных признаках показало, что значение r2 не изменилось. Это подтверждает, что умножение матрицы признаков на случайную (рандомную) матрицу преобразовывает данные и не влияет на качество оценки модели.

**Навыки и инструменты:**

Python, Pandas, Matplotlib, NumPy, SciPy, предобработка данных, работа с алгоритмами преобразования матриц.

**Статус проекта:** Завершен.