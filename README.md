# react-2024-05-13

## Дз1

1. Создать репозиторий(Публичный) на github
2. Создать ветку с названием - lecture-1/hw
3. Создать проект(используем vite - https://vitejs.dev/guide/#scaffolding-your-first-vite-project)
4. Очистить проект
5. Скопировать себе в проект мокковые данные(materials/mock.js в этом проекте)
6. Отобразить все рестораны из моковых данных. Отображаем рестораны друг за другом.
   1. Название ресторана
   2. Заголовок - Меню (h3)
   3. Список названий блюд (используем тег ul и li)
   4. Заголовок - Отзывы (h3)
   5. Список текстов отзывов (используем тег ul и li)
7. Создать компонент Header и Footer. Разместить их до и после ресторанов соответственно;
8. Сделать коммит
9. Запушить
10. Открыть ПР из ветки с дз в ветку main
11. Отправить ссылку на ПР в ветку дз 1 в Discord

## Дз2

1. Добавить счетчик в блюдо. Кнопки +,- и числом количество. Дефолтное значение 0. Максимальное 5, минимальное 0.
2. Добавить проверки(условный рендеринг) на некорректные пропсы(на свое усмотрение)
3. Доп задание. Реализовать табы - кнопки с названием ресторана, по одной на каждый ресторан. Кнопки отображаем между хедером и рестораном. Единовременно отображаем только 1 ресторан. Дефолтно отображаем первый. По клику на кнопку отображаем соответствующий ей ресторан. При повторном клике на активную кнопку ничего не происходит.

## Дз3

1. Пересмотреть лекцию
2. Сделать хук useCount(самостоятельно)

# Дз4

1. Сделать форму отзыва:
   1. Состоит из 3 контролов: имя, текст, рейтинг и кнопки сохранить
   2. Рейтинг отдельный компонент рисующий 5 кнопок с цифрами от 1 до 5. (Вспомните разбор компонента Counter)
   3. По клику на кнопку "сохранить" форма сбрасывается
2. Доп задание. Размножить активный ресторан, чтобы на странице появился длинный скролл и сделать "скролл прогресс". Подробный рассказ был в конце лекции. Демо тут - https://www.cssscript.com/demo/scroll-progress-bar/
