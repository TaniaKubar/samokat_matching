# Векторный поиск в задаче матчинга
## Данные
В нашем распоряжении датасет с векторами, описывающими некоторые характеристики товара (его изображение, текстовая информация).
Данные представлены в следующем виде:
* Id - идентификационный номер вектора
* Target - идентификационный номер вектора из таблицы base, с которым есть матч
* 0-71 - координаты векторов
## Задача
Сопоставить векторы друг с другом. Для этого необходимо провести исследовательский анализ данных, их предобработку и оптимизировать векторный поиск для достижения максимального значения полноты. Используемая метрика Recall@10 - означает общую сумму найденных в топ10 кандидатов матчей / общую сумму матчей.
## Используемые библиотеки
*faiss pandas numpy matplotlib seaborn sklearn*
