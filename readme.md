# Учебный проект "How to learn"
### Проектная работа 1 курса, спринт 1 и 2
### по профессии ["Веб-разработчик"](https://practicum.yandex.ru/profile/web/) образовательной платформы [ЯндексПрактикум](https://practicum.yandex.ru)
#### поток №39, группа "Purple"
#### старт обучения по основной программе - 14.11.2021 года

## Использовано:
1. Сетка: flex, абсолютное позиционирование, flex column-gap;
2. Файловая структура проекта организована по БЭМ-схеме Nested;
3. Декоративные изображения подключены как фон;
4. Анимация элементов: вращение и изменение прозрачности при наведении;
5. iframes для вставки видео из Youtube;
6. Семантическая верстка;

## Цветовая схема:
* серый (темный фон) #1f1f1f
* серый (светлый фон) #f2f2f2
* синий (ссылки, фигуры) #2f80ed
* черный (текст) #000000

## Пошагово:
#### Спринт 1 (16.11.2021 - 18.11.2021):
1. Семантическая разметка по текстам из texts.md;
2. Определение блоков, элементов блоков, модификаторов по брифу; селекторы для тегов по БЭМ;
3. Подключение контекстных изображений, alt текст;
4. Базовая стилизация:
* размеры, начертание шрифтов;
* высота строки;
* цвет текста и фона блоков;
5. Блок header:
* весь блок - flex-контейнер;
* все элементы, кроме заголовка спозиционированы абсолютно;
* заголовок выровнен по центру поперечной оси flex-контейнера;
* для заголовка и подзаголовка сброшены браузерные внешние отступы;
* для синего квадрата и текстовых блоков задан z-index;
6. Блок digits:
* весь блок - flex-контейнер;
* блок table - неупорядоченный список, flex-контейнер;
7. Блок feynman:
* изображение подключено как фон для блока;
* feynman__link спозиционировано абсолютно
8. Блок kaufman:
* блок table - неупорядоченный список, flex-контейнер;
* блок kaufman__triangle позиционирование абсолютное, изображение как фон блока;
9. Блок footer:
* весь блок - flex-контейнер;
* footer__columns - flex-контейнер;
* footer__column-links  - неупорядоченные списки;

#### Спринт 2 (01.12.2021 - ... ):
1. Организация файловой структуры по Nested БЭМ;
2. Добавлены изображения из 2 спринта;
3. Разметка новых секций, упорядочивание секций;
4. Анимация в header и kaufman;
5. Семантическая разметка блоков 2 спринта;
6. Ссылки становятся прозрачными при наведении мышки;
7. Глобальный блок section, для выравнивания содержимого блока по центру;
8. Вендорные префиксы, дополнение для VSCode Autoprefixer, настройки: "last 4 versions","ie >= 9", "> 5%";
9. Исправлено: Изображение для логотипов в header и footer подключены как фоновое изображение для ссылки;
10. Исправлено: Вместо тега cite для khan__quote-author использован тег p;
11. Исправлено: Общие стили для блоков footer__column перенесены в элемент footer__column;
12. Исправлено: Убран лишний внутренний отступ справа для блока header;
13. Исправлено: Фиксированная ширина для блока khan__container;
14. Исправлено: Задана максимальная ширина текстового элемента two-columns__brief вместо фиксированной и ширина 100%, чтобы не потерять отображение верстки при небольшом количестве теста внутри элемента;
15. Исправлено: Добавлена координата left:0 для блока video__iframes;
16. Исправлено: Фиксированная ширина для блока cards;
17. Исправлено: Добавлено object-fit: cover и object-position: center для header__main-illustration;

### Планы по доработке:
1. Добавить блок с обучающими курсами, например:
* ["Как учиться эффективно - Полина Кривых x I Love Economics" на платформе Stepik (бесплатно)](https://stepik.org/course/99892/promo?search=836445343)
* ["Как учиться эффективно. Большой курс" на платформе Деловая Среда Сбер (399 руб.)](https://dasreda.ru/learn/courses/kak-uchitsya-effektivno-bolshoj-kurs)
* ["Мастерство учиться" от издательства МИФ (бесплатно)](https://www.mann-ivanov-ferber.ru/courses/study-course/)
