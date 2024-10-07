# Fin
Сравнение двух подходов к предсказанию цен акций компаний


В этом проекте мы исследовали методы предсказания цен акций четырех крупных компаний, сравнивая два подхода: обучение отдельной модели для каждой компании и обучение одной модели на общих данных. 
Гипотеза заключалась в том, что 2000 записей может оказаться недостаточно для эффективного обучения отдельной модели с использованием CatBoost.

Задачи проекта

Собрать данные о ценах акций четырех крупных компаний.
Подготовить данные для обучения моделей.
Обучить модели:
Одна модель на общих данных
Отдельные модели для каждой компании
Сравнить качество предсказаний, используя метрики ошибок.
Проанализировать результаты.


Результаты
После обучения и тестирования моделей были получены следующие результаты:

Ошибка большой модели на 25% меньше, чем средняя ошибка моделей, обученных под конкретную компанию.
Были обнаружены модели, которые значительно превзошли других в качестве предсказаний, а также модели с заметно худшими результатами

Выводы
Наши результаты подтвердили гипотезу о том, что даже при ограниченном количестве записей, обучение на общем наборе данных может дать более стабильные и предсказуемые результаты, чем обучение на ограниченных данных конкретной компании. 
С другой стороны, наличие среди малых моделей тех, что показывают качество значительно выше общей модели не позволяет сделать однозначный вывод об эффективности подходов