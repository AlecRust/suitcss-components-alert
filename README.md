# SUIT CSS components-alert

A SUIT CSS component that provides a structural UI alert template to be
extended with modifiers.

Read more about [SUIT CSS's design principles](https://github.com/suitcss/suit/).

## Installation

* [yarn](https://yarnpkg.com/): `yarn add suitcss-components-alert`
* [npm](https://www.npmjs.com/): `npm install suitcss-components-alert`
* Download: [zip](https://github.com/AlecRust/suitcss-components-button/releases/latest)

## Available classes

### Component structure

* `Alert` - [core] The core alert component

### Modifiers

* `Alert--info` - Applies info colours to the alert
* `Alert--success` - Applies success colours to the alert
* `Alert--danger` - Applies danger colours to the alert
* `Alert--warning` - Applies warning colours to the alert

## Configurable variables

* `--Alert-borderColor`
* `--Alert-borderWidth`
* `--Alert-padding`

* `--Alert--info-backgroundColor`
* `--Alert--info-borderColor`
* `--Alert--info-textColor`

* `--Alert--success-backgroundColor`
* `--Alert--success-borderColor`
* `--Alert--success-textColor`

* `--Alert--danger-backgroundColor`
* `--Alert--danger-borderColor`
* `--Alert--danger-textColor`

* `--Alert--warning-backgroundColor`
* `--Alert--warning-borderColor`
* `--Alert--warning-textColor`

## Use

Examples:

```html
<div class="Alert">
  This is a default alert.
</div>
```

```html
<div class="Alert Alert--success">
  This is a success alert.
</div>
```

### Theming / extending

The CSS is focused on common structural requirements for alerts. You can extend it
with application-specific theme styles in your app.

## Testing

```
yarn install
```

To generate a build:

```
yarn build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](https://stylelint.io/)

```
yarn lint
```

To generate the testing build.

```
yarn build-test
```

To watch the files for making changes to test:

```
yarn watch
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome
* Firefox
* Opera
* Safari
* Internet Explorer 9+
