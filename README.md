# Проектная работа по анализу данных

## Информация о проекте  

**Работу выполнили**:
* Василов Тимур, 11-909
* Ромаданский Кирилл, 11-909

**Тема работы**: Ассоциативные правила для поиска аномалий

**Датасет**: Market_Basket_Optimisation.csv содержит данные о произведенных в магазине транзакциях. Всего в датасете представлено * строк - транзакций, состощих из списка товаров

**Цель**: Выявить ассоциативные правила и применить их для поиска аномалий

**Блокнот с проектом**: *


**Полное описание проекта с объяснением всех шагов** находится в блокноте Association_rules.ipynb  

</br>  

## Общее описание проекта  

1. Представляем датасет в виде денормализованной "плотной" таблицы Pandas DataFrame с помощью One-Hot кодирования
2. Анализируем датасет, чтобы определить распределние частот появления всех товаров в транзакциях 
3. Подключаем библиотеку mlxtend для расчета ассоциативных правил
4. Используя алгоритм Apriori, строим ассоциативные правила, анализируем полученный результат
5. ...
6. ...

