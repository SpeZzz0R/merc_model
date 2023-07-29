# Модель прогнозирования стоимости автомобилей Мерседес


## О проекте
Модель, предсказывающая стоимость автомобилей марки Мерседес. Модель разработана на основе библиотеки CatBoost.


## Используемые технологии
- Google Colab / Jupyter Notebook
- Python
- Pandas
- Phik
- Matplotlib
- Shap
- Scikit-learn
- CatBoost


## Результаты анализа данных	
В ходе проведенного анализа на основе человеческого обучения получены следующие результаты:
- стоимость автомобиля имеет прямую линейную зависимость по следующим параметрам: год производства ("year"), объем двигателя ("engineSize");
- стоимость автомобиля имеет обратную линейную зависимость по следующим параметрам: удельный расход топлива ("mpg"), пробег ("mileage").
Другие параметры не так сильно влияют на цену.

Полученные зависимости находят свое отражение в реальной жизни. Чем автомобиль новее, чем объем двигателя больше, тем он стоит выше. Чем расход топлива больше (яркий пример - спортивные автомобили), тем стоимость выше.

	
Все результаты подтверждаются машинным обучением. 
Показатели точности модели:
- Mean_Absolute_Error = 1508 $; 
- Mean_Absolute_Percentage_Error = 6.26 %.
  



==============================

> Автором проекта является data scientist
> 
> Запесочный Владислав.
> 
> Страница на github: https://github.com/SpeZzz0R  
> 
