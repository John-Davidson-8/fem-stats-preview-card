# Frontend Mentor - Stats Preview Card Component

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

## Overview

-Create a responsive card containing and image with opacity used.

### Screenshot

![image of stats preview card](./images/screenshot%20-stats-preview-card.png)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-card-built-with-css-flexbox-gW3JDAy72Q

- Live Site URL:https://fem-stats-preview-site.netlify.app/

## My process

- Used Visual Studio Code, Figma and Firefox Developer Edition

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox

### What I learned

Two challenges stuck out for me during this project. The first was learning to

# Interesting code

- I learned numerous aspects to html and css as I built this project. One aspect was how to add a transparent overlay to an image. This was done using the mix-blend-mode and opacity tools in css. The html and css code is shown below. The idea is to add the colour to "below" the image in the image-container which wraps the image.

```html
<div class="image-container">
  <img src="./images/image-header-mobile.jpg" alt="office workers at desks" />
</div>
```

-Below is CSS that adds effect to image.

```css
.image-container {
  background-color: hsl(277, 64%, 61%);
}
img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  overflow: hidden;
  border-top-right-radius: 0.5rem;
  border-top-left-radius: 0.5rem;
  mix-blend-mode: luminosity;
  opacity: 0.5;
}
```

### Continued development

As I completed this project I learned that individual elements such as headings and paragraphs should not have padding, but vertical margins only. It is better to use the gap property if using Flex-box for this.

### Useful resources

- The following short video instructs how to add screenshots to VSC's README file. https://www.youtube.com/

## Author

- Frontend Mentor - [@John-Davidson-8](https://www.frontendmentor.io/profile/John-Davidson-8)

## Acknowledgemnets

- Big shout out to Grace in the Frontend Mentor Slack community for all her invaluable help.
