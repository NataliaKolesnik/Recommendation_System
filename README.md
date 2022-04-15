# Рекомендательная система

 **kaggle:**  NatashaVK

**Цель:** Определить понравится ли пользователю товар на основе истории его отзывов.

**Задача:** построить модель рекомендательной системы, которая будет предсказывать рейтинг покупатель-товар, предложить варианты решения проблемы  холодного старта. 

**Данные:**  
      Находятся https://www.kaggle.com/competitions/recommendationsv4/data 

      1. train.csv - история оценок пользователя вместе с его обзором, 
      2. meta_Grocery_and_Gourmet_Food.json - информация о продуктах
      3. test.csv - тестовая выборка, для проверки качества модели на Leaderboard (метрика RocAuc)
      Для запуска ноутбука их необходимо скачать и положить в папку /data
      
 **В ходе работы:**
 1. Проведен анализ данных
 2. Сформированы новые признаки
 3. Для обучения использовалась библиотека LightFM. Было создано несколько моделей с разными наборами признаков.
 4. Сформирован файл submission_pred.csv для загрузки на лидерборд
 5. Подведены итоги

