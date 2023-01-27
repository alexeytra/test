Разработать интерфейс для сайта FrontendNews, состоящий из двух страниц.

## Продуктовые требования

### Главная страница

- Должна содержать хедер и основную часть
- Показывает последние 10 новостей в виде списка, отсортированного по дате, самые свежие сверху.
- Добавить кнопки для сортировки (под дате, по рейтингу)
- Должен быть поиск по названию
- Каждая новость содержит:
    - название
    - рейтинг
- ник автора и аватар
- дату публикации
- По клику на новость происходит переход на страницу новости

### Страница новости

- Должна содержать:
    - ссылку на новость
    - заголовок новости
    - дату
    - автора
    - счётчик количества комментариев
    - список комментариев в виде дерева
- Корневые комментарии подгружаются сразу же при входе на страницу, вложенные - по клику на корневой.
- На странице должна быть кнопка для возврата к списку новостей

## Технические требования

- Приложение должно быть разработано с использованием React (функциональные компоненты, хуки) и Redux (Можно Redux Toolkit), Redux Thunk
- Можно использовать CRA или Vite
- Придерживать компонентного подхода, при необходимости декомпозировать логику
- Для api использовать mock данные в папке public/data.json (т.е нужно создать такой файл со структурой и заполнить его) или использовать mock api - https://mockoon.com/ или другой способ (свой бек писать не нужно)
- Роутинг выполнен с использованием  [React Router](https://github.com/ReactTraining/react-router/releases/tag/v5.0.0)
- Стили на чистом CSS, главное, чтобы было красиво и адаптивно (можно использовать flex, grid)
- Пакетный менеджер  `npm`
- Приложение должно запускаться по адресу  `localhost:3000`  командой  `npm start`
- При переходах по ссылкам страница не перезагружается
- Исходный код решения должен быть выложен с вашего аккаунта на  [Github](http://github.com/)

## Опциональные задания

- Заменить CSS на SCSS
- Использование TypeScript
- Покрытие кода юнит-тестами
