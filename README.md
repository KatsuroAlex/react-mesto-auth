# Проект "Место" на React с авторизацией и регистрацией
[**Mesto-react-auth**](https://katsuroalex.github.io/react-mesto-auth) (открыть проект в браузере)

## Описание проекта
данный проект представляет собой интерактивную страницу. В этот сервис можно добавлять фотографии интересных мест, удалять их и ставить лайки.
Проект портирован на Реакт, и теперь в него добавлен функционал авторизации и регистрации пользователя.

## Основной функционал
* авторизация и регистрация пользователя,
* отображение информации о пользователе и карточек на основе данных с сервера,
* возможность редактирования данных профиля и смены аватара пользователя,
* добавление новой карточки,
* постановка/снятие лайка,
* возможность удаления только карточек текущего пользователя,
* в форму редактирования профиля подставляются текущие данные.

## Инструменты и технологии
* HTML5,
* CCS3,
* JavaScript (ES6),
* React (Create React App, разметка портирована в JSX, функциональные компоненты и хуки),
* создан контекст текущего пользователя,
* выполнено поднятие стейта из компонент Main и Card,
* использован React Router,
* использован объект history,
* проводиться верификация данных с помощью LocalStorage,
* при работе с формами используются управляемые компоненты или ref,
* сайт адаптирован под разные расширения экранов,
* flexbox,
* grid,
* БЭМ (наименование классов и организация файловой структуры),
* Webpack.

## Планы по доработке
- [X] реализовать бургер-меню,
- [X] реализовать валидацию форм.

### Установка и запуск
`npm i` - установка зависимостей  
`npm run start` - запуск проекта  
`npm run build` - запуск сборки проекта  