# Recipes (Redux)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size.
- Search recipe list.
- Add recipes to favorite recipe section.
- Remove recipes from favorite recipe section.

### Screenshot

![](./screen.jpg)

### Links

- Live Site URL: [View](https://recipesredux.netlify.app/)

## My process

- The `action.payload` property is used to hold additional data that the reducer might need to carry out a given action. The name `payload` is simply a convention, and its value can be anything!
- The spread syntax (`...`) and [array](https://www.codecademy.com/resources/docs/general/data-structures/array) methods such as .`map()`, `.slice()`, and `.filter()` can be used to immutably update the state of a complex app.
- _Reducer composition_ is a design pattern for managing a Redux store with multiple slices.
- The _root reducer_ delegates actions to slice reducers that are responsible for updating only their assigned slice of the store’s state. The root reducer then reassembles the slices into a new state object.
- `combineReducers()` is a [method](https://www.codecademy.com/resources/docs/general/method) provided by the `redux` library that accepts a collection of reducer functions and returns a `rootReducer` that implements the reducer composition pattern.
- In a Redux application, slice reducers are often written in separate files. This pattern is known as [Redux Ducks](https://github.com/erikras/ducks-modular-redux).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-Responsive Design
- JavaScript - Scripting language
- [React](https://reactjs.org/) - JS library

### What I learned

This was a class project to learn strategies for complex state of Redux.

### Continued development

maybe use later

## Author

- Website - [Cameron Howze](https://camkol.github.io/)
- Frontend Mentor - [@camkol](https://www.frontendmentor.io/profile/camkol)
- GitHub- [@camkol](https://github.com/camkol)
- LinkedIn - [@cameron-howze](https://www.linkedin.com/in/cameron-howze-28a646109/)
- E-Mail - [cameronhowze4@outlook.com](mailto:cameronhowze4@outlook.com)
