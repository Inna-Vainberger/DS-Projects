Задача:
Разработать предсказательную модель температуры расплавленного состояния сплава, которая поспособствует бизнесу в работе над своими издержками.

Описание процесса
Расплавленную сталь заливают в ковш и подогревают до нужной температуры графитовыми электродами. Из сплава выводится сера (десульфурация), добавлением примесей корректируется химический состав и отбираются пробы. При каждом цикле производится измерение температуры расплава.

Предоставлены данные:
-  об электродах;
-  о подаче сыпучих материалов (объём);
-  о подаче сыпучих материалов (время);
-  о продувке сплава газом;
-  результаты измерения температуры;
-  о проволочных материалах (объём);
-  о проволочных материалах (время).

План работы:
- объедиить данные для формирования фичей и цели
- выделить обучающий и тестовый датасеты 
- очитстиь данные от выбросов в обуч датасете
- построить модель и оценить значение МАЕ 
- оценить МАЕ для выбранной модели на тестовой выборке

Используемые библиотеки:
Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn, Xgboost
