Драфт документа матрицы компетенций для разработчиков FrontEnd в SberMarket

## Junior

**HTML**:

1. Валидация документа:  doctype, типы валидации
2. Head: описание тега и его целей; метатеги
3. Семантичная верстка: зачем нужна, примеры тегов
4. Img vs background-image
5. Как работают формы, связанные теги
6. Доступность, aria-атрибуты
7. БЭМ

**CSS**:

1. Что такое CSS, способы задания стилей (4 способа)
2. Блочные и строчные элементы: описание, отличия, как ведет себя margin
3. Стили по умолчанию: как это мешает кроссбраузерности, reset, normalize
4. Виды селекторов, приоритетность
5. Респонсивная, адаптивная верстка, медиа запросы
6. transform - что за свойство
7. Работа с em, rem, %
8. Свойства width и height, заданные в %
9. Типы позиционирования элементов, поток документа
10. Как подключить кастомные шрифты
11. Flexbox: grow, shrink, align-items, justify-content, wrap, direction
12. Функция calc

**JavaScript:**

1. Типы данных, примитивы и ссылочные типы
2. Отличия var, let, const
3. Виды циклов, особенности
4. Строгое/нестрогое сравнение
5. Свойства и методы массивов, проверка на массив, использование методов массивов в случае массивоподобных коллекций
6. Замыкание
7. Function declaration, function expression
8. Привязка контекста
9. Синхронные и асинхронные операции
10. Промисы: цепочки, методы, асинхронная часть
11. Деструктуризация, спред-оператор
12. Стрелочные функции, отличия от обычных функций
13. IIFE

**Технологии, библиотеки, инструменты**

1. React: JSX, знать процесс рендера, основные жизненные циклы в классовых компонентах, хуки, особенности рендера массивов элементов, пропсы,  работа с состоянием, роутинг
2. Redux, Redux-Toolkit. Базовое понимание flux
3. SCSS
4. Eslint, Prettier
5. Antd
6. Axios
7. Formik
8. Git: принцип работы; команды push, pull, rebase, cherry-pick, reset
9. Работа с Chrome devtools. Базовые возможности: изменение стилей на лету, работа с консолью (просмотр ошибок, логирование)
10. TypeScript: базовое понимание типов, умение пользоваться встроенными дженериками, Unions, Type Guards. TypeScript + React
11. Веб: что такое HTTP, как устроены cookie, REST API
12. Автоматическое тестирование: зачем это нужно, что такое модульные, интеграционные, e2e тесты

## Middle

**CSS**

1. grid: template-columns,  template-rows, gap, auto-fit
2. Как избежать лишних перерисовок
3. Css-переменные vs scss-переменные
4. Css-анимации

**JavaScript**

1. Геттеры и сеттеры
2. Дескрипторы свойств объектов
3. Object to primitive
4. Генераторы
5. EventLoop
6. Сборщик мусора

**TypeScript**

1. В чем польза статической типизации
2. Как происходит процесс компиляции TypeScript в JavaScript
3. Дженерики
4. Разница между type и interface
5. Ключевое слово infers
6. enum
7. keyof
8. typeof
9. Условные типы
10. Утилиты Partial, Omit, Required, Record, Pick, ReturnType

**React**

1. Зачем нужен React, какие преимущества он дает
2. Оптимизация перерендера
3. Виртуализация объемных списков, таблиц и т.п.
4. Refs: зачем могут понадобиться, почему стоит избегать

**Тестирование**

1. Что означает величина покрытия тестами
2. Нужно ли стремиться к 100% покрытию
3. Что такое “плавающий баг”
4. TDD: в чем заключается подход, плюсы и минусы
5. Нужно ли тестировать приватные методы классов?

**Паттерны проектирования**

1. MVC/MVP/MVVM
2. Синглтон
3. Фабрика, абстрактная фабрика, фабричный метод
4. Фасад
5. Декоратор

**Технологии, библиотеки, инструменты**

1. Next.js
2. Thunk
3. Saga
4. Yup
5. Joi
6. Linux: базовые навыки по администрированию
7. Вебсокеты
8. JSDoc
9. PWA
10. Webpack: конфигурация, плагины, лоадеры
11. Регулярные выражения
12. Работа с Chrome devtools: дебаггер, профилирование
13. Работа с изображениями: как картинки влияют на загрузку страницы

**Базовые знания**

1. ООП
    * Что такое класс, объект класса
    * Абстракция
    * Наследование
    * Инкапсуляция
    * Полиморфизм
2. SOLID
    * Single Responsibility principle
    * Open Closed principle
    * Liskov Substitution principle
    * Interface Segregation principle
    * Dependency Injection principle
3. DRY
4. KISS
5. Функциональное программирование
    * Функции высшего порядка
    * Чистые функции, сайд эффекты
    * Идемпотентность
    * Иммутабельность
    * Рекурсия
6. Императивный и декларативный подход

## Senior

**Технологии, библиотеки, инструменты**

1. Веб воркеры: что это, сферы применения
2. Canvas. Недостатки в сравнении с HTML
3. WebGL: базовые понятия
4. Node.js: базовые знания, умение спроектировать простой REST сервис
5. SQL на базовом уровне
6. React Native: базовые знания
7. Docker: теоретические знания,  умение завернуть приложение в контейнер
8. CI/CD: теория + умение настроить простой пайплайн
9. Angular/Vue: теоретические знания, плюсы и минусы в сравнении с React

**Алгоритмы/структуры данных**



1. Умение определить time/space complexity
2. Умение реализовать оптимальный алгоритм для решения задачи
3. Классические структуры данных: связанный список, дерево, стек, очередь, граф
