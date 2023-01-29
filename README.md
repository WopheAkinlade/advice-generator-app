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

**Note: Delete this note and update the table of contents based on what sections you keep.**

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

**Note: These are just examples. Delete this note and replace the list above with your own choices**

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
const [adviceObject, setAdviceObject] = useState<adviceObject>({
    id: 1,
    advice: "",
  }); // A global state was created 

  setAdviceObject(adviceObject); // The data in the promise function can now be accessed all over App as a global state 
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

## Author

- Website - [Wofe Akinlade](https://wophe1.netlify.app/)
- Frontend Mentor - [@WopheAkinlade](https://www.frontendmentor.io/profile/WopheAkinlade)
- Twitter - [@NinjaAkuma_](https://www.twitter.com/NinjaAkuma_)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Many thanks to my good friend [Don](https://github.com/Multimarix) who helped me out with some of the React code I was unfamiliar with. 

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
