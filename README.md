#Лекция 1 Введение в Web

Основные темы курса

• Фундаментальный web

• Advanced JavaScript

• Клиентская разработка (vanilla js)

• Серверная разработка (node.js)

• Real-time сообщения (polling, websocket)

Базовый сценарий работы web-приложения

• Пользователь вводит URL.

• Браузер загружает HTML-документ.

• Браузер парсит HTML и загружает дополнительные ресурсы.

• Браузер рендерит страницу.

URL

Пример: http://mi-ami.ru:8080/profile/account.html?gender=male&age=13#comments

Компоненты

• Протокол

• Доменное имя

• Порт

• Путь

• Query-параметры

• Якорь

HTTP

• Протокол клиент-серверного взаимодействия.

• Методы: GET, POST, PUT, DELETE.

• Статусы ответа:

◦ 1xx (информационные)

◦ 2xx (успех)

◦ 3xx (перенаправление)

◦ 4xx (ошибка клиента)

◦ 5xx (ошибка сервера)

HTML

Основные теги

• html

• head

• body

• h1-h6

• p

• div

• span

• a

• img

• ul/ol/li

• form

• input

CSS

Способы задания стилей

• Внешний файл

• Тег style

• Атрибут style

Селекторы

• Универсальный

• По тегу

• По классу

• По id

• Контекстные

• Дочерние

• Соседние

• Группировка

Приоритеты стилей

• Специфичность

• Важность (!important)

Лекция 2 JavaScript

Основы JavaScript

• Переменные: let, const, var.

• Типы данных: примитивы (string, number, boolean, symbol, null, undefined, bigint) и объекты.

• Операторы: математические, сравнения, логические.

Условные операторы

• if-else

• Тернарный оператор

Циклы

• while

• do-while

• for

Функции

• Function Declaration vs Function Expression

• Стрелочные функции

• Замыкания и лексическое окружение

Объекты и массивы

Создание объектов

• Литерал

• Конструктор

Методы массивов

• push

• pop

• shift

• unshift

• slice

• splice

• map

• filter

• reduce

• sort

Классы

• Синтаксис классов

• Наследование

• Статические методы

• Приватные свойства

Модули

• Экспорт и импорт: export, import.

• Динамический импорт.

Лекция 3 Углубленный JavaScript

Асинхронность

• Event Loop: макротаски, микротаски.

• Промисы: then, catch, finally, Promise.all, Promise.race.

• Async/await.

Обработка ошибок

• try-catch-finally.

• Пользовательские ошибки.

Регулярные выражения

• Синтаксис: new RegExp, /шаблон/флаги.

• Методы: test, exec, match, replace.

События

Типы событий

• Мыши

• Клавиатуры

• Формы

Обработчики

• addEventListener

• removeEventListener

Всплытие и погружение

Лекция 4 Архитектура Web

Критические этапы рендеринга

• Загрузка HTML.

• Построение DOM.

• Построение CSSOM.

• Формирование Render Tree.

• Компоновка (layout).

• Отрисовка (paint).

Архитектурные решения

• MVC: Модель, Представление, Контроллер.

• Роутинг: History API.

• CSS-архитектура: BEM, CSS Modules, JSS.

Лекция 5 Node.js

Основы Node.js

• Среда выполнения JavaScript на сервере.

• Модули: http, fs, path, os.

• Создание сервера.

Nest.js

• Фреймворк для серверных приложений.

• Контроллеры, сервисы, Dependency Injection.

TypeScript

• Статическая типизация.

• Интерфейсы, декораторы.

Лекция 6 AJAX

XMLHttpRequest

• Синхронные и асинхронные запросы.

• Обработка ответов.

CORS

• Правило ограничения домена.

• Заголовки: Origin, Access-Control-Allow-Origin.

Хранение данных

• Куки

• Web Storage

• IndexedDB

Лекция 7 Асинхронный JavaScript

Promise

• Состояния: pending, fulfilled, rejected.

• Цепочки вызовов: then, catch.

Fetch API

• Упрощенный интерфейс для HTTP-запросов.

• Опции: method, headers, body.

Транспайлинг и сборка

• Babel: преобразование современного JS в старый.

• Bundler (Vite): объединение файлов в bundle.
