# SCSS Function Line Height

A package for integrating the text line height calculation function.

![npm](https://img.shields.io/npm/v/@bu0nq/scss-function-line-height?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/scss-function-line-height?style=for-the-badge)

Documentation: [EN](README.md) | [RU](README.RU.md)

___

## Installation

You can install the package automatically using NPM:

```
npm i @bu0nq/scss-function-line-height
```

## Usage

To use the package, import it into your project:

```scss
@use "@bu0nq/scss-function-line-height" as *;

.demo {
    line-height: line-height(16px);
}
```

## Changing the namespace

You can change the namespace during function import and use the function with a different namespace:

```scss
@use "@bu0nq/scss-function-line-height" as function;

.demo {
    line-height: function.line-height(16px);
}
```

## Changing the variables

You can redefine the default values for the specified variables when importing the function:

```scss
@use "@bu0nq/scss-function-line-height" as * with (
    $interval: 1.5,
);
```
