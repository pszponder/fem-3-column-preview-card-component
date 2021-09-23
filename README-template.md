# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot of Completed Project](./documentation/completed-project.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Start with mobile version of website, then add media-queries using min-width to expand the website for desktop
- Create the structures of the HTML first, then move on to the CSS
- Create a seperate reset.css file for common css reset parameters.
- In the beginning of style.css, create variables for colors, and width and height which are reused in other areas of code
- Step through the HTML from top to bottom and style the CSS based on the order that the elements appear in the HTML.
- Use the BEM naming convention for classnames.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

When using Flexbox, it is important to understand the actual width of the parent flex container. The flex items by default will try to fit inside the available space in the flexbox.

When using flexbox, it is a good idea to either specify width of the elements, or use `flex`, but not both.

When creating the border radius on the parent element (main) I had to use `overflow: hidden` to show the border radius. By default, since the child element (section) were the same size as the parent element, the child elements were overflowing and obscuring the border radius defined on the parent element.

If you are repeatedly using the same values (like background colors), you can use css custom variables so that you can reuse those values and only update the value once.

```css
:root {
  --card--color-suv: hsl(184, 100%, 22%);
}

.card--color-suv {
  background-color: var(--card--color-suv);
}
```

### Continued development

I plan to continue improving my knowledge of flexbox as well as HTML and CSS structuring and styling. I learned to use BEM and semantic HTML but need more practice.

For this particular project, there is probably a way to refactor the code to make it cleaner.

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - I always reference this guid when I need to look back at any flexbox properties, it is super helpful.

## Author

- Website - [Piotr Szponder](https://github.com/pszponder)
- LinkedIn - [Piotr Szponder](https://www.linkedin.com/in/piotrszponder/)
- Frontend Mentor - [@pszponder](https://www.frontendmentor.io/profile/pszponder)
- Twitter - [@PSzponder](https://twitter.com/PSzponder)

```

```
