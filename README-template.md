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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshots)

### Links

- Solution URL: [Add solution URL here](https://github.com/HouR-BeaN/3Column.git)
- Live Site URL: [Add live site URL here](hhttps://3-column-tau.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow- For styles

### What I learned

Here I learn how CSS flexbox works. It help me to manage the cards using flex-direction property. Also, I became more familliar with padding border and margin. While doing this project I also lear, how to change styles using css.

These are the code snippets I am proud of:

```css
#sedan-btn {
  color: hsl(31, 77%, 52%);
}
#sedan-btn:hover {
  background-color: hsla(0, 0%, 100%, 0);
  color: hsl(0, 0%, 95%);
  border: 1px solid hsl(0, 0%, 95%);
  cursor: pointer;
}

@media only screen and (max-width: 376px) {
  .cards-container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  section {
    height: fit-content;
    margin: 60px auto;
  }
  button {
    margin-top: 0;
  }
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I want to improve my knowledge about positioning and spacing.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Arvin Delos Reyes](https://www.your-site.com)
- Frontend Mentor - [@HouR-BeaN](https://www.frontendmentor.io/profile/HouR-BeaN)
- Twitter - [@drs_rvn](https://www.twitter.com/drs_rvn)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
