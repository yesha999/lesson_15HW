Предполагается сделать следующие таблицы:
Главная таблица:
1. 1) id
2) animal_id (Таблица зверей)
    1) animal_id
    2) animal_type_id
       * Вынести типы животных в отдельную таблицу
    3) name
    4) breed_id
        * Вынести породы в отдельную таблицу
    5) color_1_id
        * Вынести цвета в отдельную таблицу
    6) color_2_id
    7) date_of_birth
   
3) outcome_id (так как одно животное может 
посетить клинику не один раз нужно сделать
отдельную таблицу посещений)
    1) outcome_id
    2) outcome_subtype_id
        * Вынести в отдельную таблицу
    3) outcome_type_id
       * Вынести в отдельную таблицу
    4) outcome_month
    5) outcome_year


2. animal_outcome (Таблица связи посещений и зверей)