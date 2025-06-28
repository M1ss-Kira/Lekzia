# Лекция 1. Введение в Web

## Основные темы курса
- **Фундаментальный web**
- **Advanced JavaScript**
- **Клиентская разработка (vanilla js)**
- **Серверная разработка (node.js)**
- **Real-time сообщения (polling, websocket)**

## Базовый сценарий работы web-приложения
1. Пользователь вводит URL.
2. Браузер загружает HTML-документ.
3. Браузер парсит HTML и загружает дополнительные ресурсы.
4. Браузер рендерит страницу.

## URL
**Пример:**  
`http://mi-ami.ru:8080/profile/account.html?gender=male&age=13#comments`

**Компоненты:**
- Протокол (`http`)
- Доменное имя (`mi-ami.ru`)
- Порт (`8080`)
- Путь (`/profile/account.html`)
- Query-параметры (`?gender=male&age=13`)
- Якорь (`#comments`)

## HTTP
- Протокол клиент-серверного взаимодействия.
- **Методы:** `GET`, `POST`, `PUT`, `DELETE`.
- **Статусы ответа:**
  - `1xx` (информационные)
  - `2xx` (успех)
  - `3xx` (перенаправление)
  - `4xx` (ошибка клиента)
  - `5xx` (ошибка сервера)

## HTML
**Основные теги:**
```html
<html>, <head>, <body>, <h1>-<h6>, <p>, <div>, <span>, <a>, <img>, <ul>/<ol>/<li>, <form>, <input>
```

## CSS
**Способы задания стилей:**
- Внешний файл (`<link rel="stylesheet" href="style.css">`)
- Тег `<style>`
- Атрибут `style="..."`

**Селекторы:**
- Универсальный (`*`)
- По тегу (`div`)
- По классу (`.class`)
- По id (`#id`)
- Контекстные (`div p`)
- Дочерние (`div > p`)
- Соседние (`div + p`)
- Группировка (`h1, h2`)

**Приоритеты стилей:**
- Специфичность (вес селекторов)
- `!important`

---

# Лекция 2. JavaScript

## Основы JavaScript
- **Переменные:** `let`, `const`, `var`.
- **Типы данных:**  
  Примитивы (`string`, `number`, `boolean`, `symbol`, `null`, `undefined`, `bigint`) и объекты.
- **Операторы:** математические, сравнения, логические.

## Условные операторы
- `if-else`
- Тернарный оператор (`condition ? true : false`)

## Циклы
- `while`
- `do-while`
- `for`

## Функции
- **Function Declaration** vs **Function Expression**
- Стрелочные функции (`() => {}`)
- Замыкания и лексическое окружение

## Объекты и массивы
**Создание объектов:**
- Литерал (`{}`)
- Конструктор (`new Object()`)

**Методы массивов:**
```js
push(), pop(), shift(), unshift(), slice(), splice(), map(), filter(), reduce(), sort()
```

## Классы
- Синтаксис классов (`class MyClass {}`)
- Наследование (`extends`)
- Статические методы (`static`)
- Приватные свойства (`#privateField`)

## Модули
- Экспорт/импорт: `export`, `import`.
- Динамический импорт (`import()`).

---

# Лекция 3. Углубленный JavaScript

## Асинхронность
- **Event Loop:** макротаски, микротаски.
- **Промисы:**  
  `then()`, `catch()`, `finally()`, `Promise.all`, `Promise.race`.
- **Async/await:**  
  ```js
  async function fetchData() {
    const data = await fetch(url);
  }
  ```

## Обработка ошибок
- `try-catch-finally`
- Пользовательские ошибки (`throw new Error("...")`)

## Регулярные выражения
- Синтаксис:  
  `new RegExp("шаблон", "флаги")` или `/шаблон/флаги`.
- Методы:  
  `test()`, `exec()`, `match()`, `replace()`.

## События
**Типы событий:**
- Мыши (`click`, `mouseover`)
- Клавиатуры (`keydown`, `keyup`)
- Формы (`submit`, `change`)

**Обработчики:**
- `addEventListener()`
- `removeEventListener()`

**Всплытие и погружение:**
- `event.stopPropagation()`

---

