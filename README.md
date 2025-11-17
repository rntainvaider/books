Соодержание
- [HTML](#html)
- [CSS](#css)
- [JAVASCRIPT](#javascript)
  - [Типы данных](#типы-данных)
  - [Методы подключения файлов js:](#методы-подключения-файлов-js)
  - [](#)
- [REACT](#react)
  - [Настройка styles.module.css React + TypeScript](#настройка-stylesmodulecss-react--typescript)
  - [Настройка svg формата React + TypeScript](#настройка-svg-формата-react--typescript)
- [REACT NATIVE](#react-native)
  - [Настройка среды разработки Expo](#настройка-среды-разработки-expo)
- [NODE JS](#node-js)
- [PYTHON](#python)
  - [Список проектов python для обучения](#список-проектов-python-для-обучения)
- [DJANGO](#django)
- [FAST API](#fast-api)
- [FLASK](#flask)

# HTML

HTML - стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере, который описывает структуру вашего документа.

# CSS

# JAVASCRIPT

ECMAScript (ES) — это стандартизированная спецификация языка программирования, на основе которой построен JavaScript. По сути, это набор правил, определяющих синтаксис, типы данных и другие основные элементы языка.

## Типы данных

- Примитивный тип данных (простой тип)
1. string
2. number
3. boolean
4. null - значение пусто или значение не известно.
5. undefined - значение не было присвоено.
6. symbol
7. bigint - большое число 2^53 - 1


- Непримитивный тип данных (сложный тип)
1. object

`typeof()` - функция определения типа данных.

JavaScript имеет динамическую типизацию, то есть если переменная имеет тип данных string, то можно поменять на тип данных number.

Бывает явное `Number('3')` и неявное `+'3'` преобразование типов. Лучше всего использовать явное.

## Методы подключения файлов js:

Файлы js подключаются при помощи тега script.

1. В теге head
2. В конце тега body

##

console.log(message) - выводит данные в console браузера.
alert(message) - выводит модальное окно в браузере.
promt(message, default) - выводит модальное окно в браузере для ввода информации.

# REACT

## Настройка styles.module.css React + TypeScript

- Нужно создать файл `src/global.d.ts` и прописать в нем:

```
declare module '*.module.css' {
  const classes: { [key: string]: string };
  export default classes;
}
```

## Настройка svg формата React + TypeScript

- Нужно создать файл `src/global.d.ts` и прописать в нем:

```
declare module "*.svg" {
  import React from "react";
  export const ReactComponent: React.FC<React.SVGProps<SVGSVGElement>>;
  const src: string;
  export default src;
}
```

# REACT NATIVE

## Настройка среды разработки Expo
1. Команда установки Expo:
```
npm i -g expo-cli
```
2. Команда для создания проекта:
```
expo init <имя_проекта>
```
3. Перейти в проект:
```
cd <имя_проекта>
```
4. Установить зависимости:
```
npm i
```
Либо
```
npm install
```

# NODE JS

# PYTHON

##  Список проектов python для обучения


# DJANGO

# FAST API

# FLASK
