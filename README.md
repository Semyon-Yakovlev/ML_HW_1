# ML_HW_1
Часть 1.

Простейший EDA и обработка признаков.
Заполнили пропуски 
Посмотрели на pairplot, heatmap(сorr).
Cильно с целевой переменно коррелирует max_power, что можно заметить на графике и в матрице корреляций.
Слабее год и объем двигателя.
Есть сильная корреляция между объемом двигателя и его мощностью.
Есть сильная корреляция между объемом двигателя и кол-вом сидений в автомобиле.

Часть 2. Модель только на вещественных признаках.
Классическая линейная регрессия с дефолтными параметрами показала R^2 = 0.59.
После стандартизации  R^2 = 0.59 не учучшило.
Lasso-регрессия R^2 = 0.59.
После добавления L1-регуляризации R^2 = 0.57 стало даже хуже.
ElasticNet R^2 = 0.57 аналогично Lasso с L1.

Часть 3. Добавление категориальных фич.
Ridge R^2 = 0.64 удалось улучшить модель

Часть 4. Feature Engineering.
После добавления фич и попытки работы над ними модель стала хуже
Ridge R^2 = 0.59

Часть Бизнесовая метрика получилась = 0.778.
Отличный результат.
Часть 5. 
predict_item.png - метод post, который получает на вход один объект описанного класса.
predict_items.png - метод post, который получает на вход коллекцию объектов описанного класса.
response.xls - результат метода predict_items.
