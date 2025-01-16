# Stepik courses rating

## Пояснение к названиям столбцов:
   - name - название курса;
   - link - ссылка на курс;
   - category - категория, из которой взят курс;
   - reviews amount - общее количество всех отзывов;
   - total score - оценка курса по 100-бальной шкале;
   - average stars count - сколько в среднем звёзд у курса (число с точностью большей, чем на сайте);
   - detail score - средняя оценка полноты отзыва (число float от 0 до 1);
   - deep score - средняя оценка глубины курса (число float от 0 до 1);
   - material quality score - средняя оценка качества материала курса (число float от 0 до 1);
   - problems quality score - средняя оценка качества задач курса (число float от 0 до 1);
   - coach skills score - средняя оценка навыков преподователя (число float от 0 до 1);
   - practice experience score - средняя оценка практической составляющей курса (число float от 0 до 1);
   - feedback score - средняя оценка обратной связи (число float от 0 до 1);
   - positive score - средняя оценка позитивности отзывов (число float от 0 до 1);
   - negative score - средняя оценка негативности отзывов (число float от 0 до 1);
   - important reviews amount - общее количество полезных отзывов о курсе;
   - positive reviews part - доля позитивных отзывов от их общего количества (число float от 0 до 1);
   - negative reviews part - доля негативных отзывов от их общего количества (число float от 0 до 1);
   - important positive reviews part - доля полезных позитивных отзывов от общего количества полезных отзывов (число float от 0 до 1);
   - important negative reviews part - доля полезных негативных отзывов от общего количества полезных отзывов (число float от 0 до 1);
   - important reviews part - доля полезных отзывов от общего количества отзывов (число float от 0 до 1).

## Дополнительная информация:
Обе таблицы содеждат одни и те же данные. В stepik.csv сортировкаа произведена по произведению оценки и количества отзывов, а в stepik_short.csv просто по оценке. Так же stepik_short.csv содержит меньше данных о курсах.

##

#### Ссылка на библиотеку, с помощью которой была произведена оценка - https://github.com/IvanKholodilo/StepikEval
