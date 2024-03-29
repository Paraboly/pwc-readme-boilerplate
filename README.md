![Built With Stencil](https://img.shields.io/badge/-Built%20With%20Stencil-16161d.svg?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjIuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MTIgNTEyOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI%2BCjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI%2BCgkuc3Qwe2ZpbGw6I0ZGRkZGRjt9Cjwvc3R5bGU%2BCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik00MjQuNywzNzMuOWMwLDM3LjYtNTUuMSw2OC42LTkyLjcsNjguNkgxODAuNGMtMzcuOSwwLTkyLjctMzAuNy05Mi43LTY4LjZ2LTMuNmgzMzYuOVYzNzMuOXoiLz4KPHBhdGggY2xhc3M9InN0MCIgZD0iTTQyNC43LDI5Mi4xSDE4MC40Yy0zNy42LDAtOTIuNy0zMS05Mi43LTY4LjZ2LTMuNkgzMzJjMzcuNiwwLDkyLjcsMzEsOTIuNyw2OC42VjI5Mi4xeiIvPgo8cGF0aCBjbGFzcz0ic3QwIiBkPSJNNDI0LjcsMTQxLjdIODcuN3YtMy42YzAtMzcuNiw1NC44LTY4LjYsOTIuNy02OC42SDMzMmMzNy45LDAsOTIuNywzMC43LDkyLjcsNjguNlYxNDEuN3oiLz4KPC9zdmc%2BCg%3D%3D&colorA=16161d&style=for-the-badge)

![WebComponent PWC README Boilerplate](https://raw.githubusercontent.com/paraboly/pwc-readme-boilerplate/repository-resources/logo.png)

[![Fully customizable readme boilerplate for web component with StencilJS via Paraboly](https://img.shields.io/badge/-Fully%20customizable%20readme%20boilerplate%20for%20web%20component%20with%20StencilJS%20via%20Paraboly-lightgrey?style=for-the-badge)](https://github.com/Paraboly/pwc-readme-boilerplate)

[![npm version](https://img.shields.io/npm/v/@paraboly/pwc-readme-boilerplate.svg?style=for-the-badge)](https://www.npmjs.com/package/@paraboly/pwc-readme-boilerplate)
[![npm](https://img.shields.io/npm/dt/@paraboly/pwc-readme-boilerplate.svg?style=for-the-badge)](https://www.npmjs.com/package/@paraboly/pwc-readme-boilerplate)
![Platform - Platform Free Web](https://img.shields.io/badge/-Web%20%7C%20Platform%20Free-blue?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

![WebComponent PWC Animated Checkbox](https://raw.githubusercontent.com/paraboly/pwc-readme-boilerplate/repository-resources/Screenshots/JSLibraryBoilerplate.png)

## [Live Codepen Example](https://codepen.io/wrathchaos/pen/dyyvRzM)

## Installation

### Script tag

- Put a script tag similar to this `<script	type="module" src="https://unpkg.com/@paraboly/pwc-readme-boilerplate@latest/dist/pwc-readme-boilerplate/pwc-readme-boilerplate.esm.js"></script>` in the head of your index.html
- Then you can use the element anywhere in your template, JSX, html etc

### Node Modules
- Run `npm install @paraboly/pwc-readme-boilerplate --save`
- Put a script tag similar to this `<script src='node_modules/@paraboly/pwc-readme-boilerplate/dist/pwc-readme-boilerplate.js'></script>` in the head of your index.html
- Then you can use the element anywhere in your template, JSX, html etc

### In a stencil-starter app
- Run `npm install @paraboly/pwc-readme-boilerplate --save`
- Add an import to the npm packages `import @paraboly/pwc-readme-boilerplate;`
- Then you can use the element anywhere in your template, JSX, html etc


# Usage

## Basic Usage

This is just an example from pwc-animated-checkbox, you need to change it !

```html
<pwc-animated-checkbox></pwc-animated-checkbox>
```

## Checkbox onCheckChange Listener Usage

### JS Way

This is just an example from pwc-animated-checkbox, you need to change it !

```js
// Multiple Checkboxes
const pwcCheckboxes = document.querySelectorAll("pwc-animated-checkbox");
pwcCheckboxes.forEach(element => {
  element.addEventListener("checkedEvent", event => {
    console.log("Event: ", event.detail);
  });
})  
// Selects the first checkbox
const pwcCheckbox = document.querySelector("pwc-animated-checkbox");
pwcCheckbox.addEventListener("checkedEvent", event => {
console.log("First Element Event: ", event.detail);
```

## Future Plans

- [x] ~~Documentation~~
- [ ] Color Customization
- [ ] Animation Bug Fix

## Authors

FreakyCoder, kuray.ogun@paraboly.com | kurayogun@gmail.com

## License

WebComponent PWC README Boilerplate is available under the MIT license. See the LICENSE file for more info.
