# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot](images/Screenshot%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass]- Scss / Sass

### What I learned

- Learned to better organize my Sass folders. This should speed things up in the future.
- The first time I worked with Figma files; need more practice with this.
- Learned a little about animation; this was fun, but it makes the site too bust for my taste.

```css
.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(4, 1fr);
  grid-template-areas: ". team-builder ." "supervisor team-builder calculator" "supervisor karma calculator" ". karma .";
  gap: 2rem;
}
```

### Continued development

Learning to use the figma files more efficiently

### Useful resources

- [Resource 1](https://dev.to/luis_sserrano/how-to-structure-your-sass-code-56nj) - This helped me organize my Sass a bit better. I really liked this pattern and will use it going forward, although it still needs a bit of tweeking.

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)

## Acknowledgments

I drew inspiration from several people's solutions. Thank you @bossthekhani for the idea for animating the cards on hover; someone else (for get who) changed the h2 on hover to reflect the card's border color. Brillant!!! Also, MelissaZhuu for encouraging me to take a second look at this project.
