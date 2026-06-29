# SCSS Function Rem

A package for integrating the `px` to `rem` conversion function.

![npm](https://img.shields.io/npm/v/@m2collective/scss-function-rem?style=for-the-badge)

___

## Installation

You can install the package automatically using NPM:

```
npm i @m2collective/scss-function-rem
```

## Usage

To use the package, import it into your project:

```scss
@use "@m2collective/scss-function-rem" as *;

.demo {
    font-size: rem(16px);
}

// Return

.demo {
    font-size: 1rem;
}
```

## Changing the namespace

You can change the namespace during function import and use the function with a different namespace:

```scss
@use "@m2collective/scss-function-rem" as function;
```

## Changing the variables

You can redefine the default values for the specified variables when importing the function:

```scss
@use "@m2collective/scss-function-rem" as * with (
    $default: 16,
);
```

## License

The MIT License (MIT). Please see the [License file](LICENSE.txt) for more information.
