# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

(https://raw.githubusercontent.com/csut1337/perfume.github.io/main/Screenshot%202023-03-13%2018.07.06.png)

### Links

- Solution URL: https://github.com/csut1337/perfume.github.io
- Live Site URL: https://csut1337.github.io/perfume.github.io/

## My process

I initially planned to do this project as a means of practicing Bootstrap while I learn enough JavaScript to begin implementing that in projects. I've found pretty quickly that I prefer my own CSS/layout to Bootstrap, however. It still ended up being the right project to undertake as the responsive components were much more elaborate than the last (Equilibrium) project I did.

I build the desktop page first- starting with the right side of the card. Once everything was in place there, I began to work on the responsive/media query component. Here, I realized the image was in fact different and had to go figure out how to accomplish that swap. I had seen the idea of a background image and media queries to accomplish this but didn't have much luck with that method. I found several tutorials using the <picture> tag and followed the one listed above.

The biggest issue I was having in the end is that neither of the images 100% fill the space within the container- the top of the image in both desktop and mobile views has some background showing through.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

This project ended up being harder than I initially expected! I had some vertical alignment issues on the desktop view initially as I forgot to declare the 'min-height: 100vh;' again (I have missed this for like an hour several projects in a row now lol.)

Beyond that, things were fairly smooth until I began working on the breakpoint image swap, which- the issues I had here were more that I hadn't learned how to do this yet. Once I found and followed an appropriate tutorial, it didn't take too long.

### Continued development

At risk of sounding like a broken record- the image swap! I will try to undertake another responsive project as the depth in this project felt outside my comfort zone.

I've been working on learning basic JavaScript in the Udemy class I'm taking but am not quite to a point where I can incorporate JS into projects yet. Depending how the timeframe on that goes I may shoot for a project including JS next, but I'm finding it difficult to pick up.

### Useful resources

- https://www.udemy.com/course/the-web-developer-bootcamp/ - This is the Udemy class I have been taking
- https://www.youtube.com/shorts/d9i68C628Nk - This was the video I followed to implement the breakpoint image swap

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/csut1337
