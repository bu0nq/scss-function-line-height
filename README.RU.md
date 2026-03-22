# SCSS Function Line Height

Пакет для интеграции функции вычисления высоты текстовой строки.

Документация: [EN](README.md) | [RU](README.RU.md)

___

## Установка

Вы можете установить пакет автоматически с помощью NPM:

```
npm i @bu0nq/scss-function-line-height
```

## Использование

Чтобы использовать этот пакет, импортируйте его в свой проект:

```scss
@use "@bu0nq/scss-function-line-height" as *;

.demo {
    line-height: line-height(16px);
}
```

## Изменение пространства имен

Вы можете изменить пространство имен во время импорта функции и использовать функцию с другим пространством имен:

```scss
@use "@bu0nq/scss-function-line-height" as function;

.demo {
    line-height: function.line-height(16px);
}
```

## Изменение переменных

Вы можете переопределить значения по умолчанию для указанных переменных при импорте функции:

```scss
@use "@bu0nq/scss-function-line-height" as * with (
    $interval: 1.5,
);
```
