# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

### Links

- Solution URL: [https://github.com/WopheAkinlade/advice-generator-app](https://github.com/WopheAkinlade/advice-generator-app)
- Live Site URL: [https://advicegeneratorbywophe.netlify.app/](https://advicegeneratorbywophe.netlify.app/)

## My process

### Built with

- [React](https://reactjs.org/) - JS library
- Typescript
- CSS custom properties
- Flexbox

### What I learned

I learned how to use `fetch` to call APIs and also how to extract data from a `Promise` function

###### Use of `fetch`

```js
const response: Promise<Response = fetch(
  "https://api.adviceslip.com/advice"
);
```

###### Extraction of data from a `Promise` function

```js
const [adviceObject, setAdviceObject] =
  useState <
  adviceObject >
  {
    id: 1,
    advice: "",
  }; // A global state was created

setAdviceObject(adviceObject); // The data in the promise function can now be accessed all over App as a global state
```

## Author

- Website - [Wofe Akinlade](https://wophe1.netlify.app/)
- Frontend Mentor - [@WopheAkinlade](https://www.frontendmentor.io/profile/WopheAkinlade)
- Twitter - [@NinjaAkuma\_](https://www.twitter.com/NinjaAkuma_)

## Acknowledgments

Many thanks to my good friend Don[(check out his Github page)](https://github.com/Multimarix) who helped me out with some of the React code I was unfamiliar with.
