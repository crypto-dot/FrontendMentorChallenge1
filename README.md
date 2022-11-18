# Frontend Mentor - Product preview card component

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Li nks](#links)
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

Desktop
<img width="1440" alt="Screen Shot 2022-11-18 at 12 39 18 AM" src="https://user-images.githubusercontent.com/78282234/202637634-12f086e5-d67a-4ed9-be91-100e67577ef0.png">

Mobile
<img width="365" alt="Screen Shot 2022-11-18 at 12 40 04 AM" src="https://user-images.githubusercontent.com/78282234/202637775-ffae378a-02d6-4d7b-b32a-5af73d1fe113.png">


### Links

- Live Site URL: [Click Me!](https://crypto-dot.github.io/FrontendMentorChallenge1/)

## My process

I worked from left to right. First I figured out how to get the image correctly cropped. This proved a little more difficult then I expected since I wanted to use the HTML5 picture element, but I realized that I could not adjust the images using css. I winded up using a div and setting the background image to the actual image needed. Then I used media queries to crop the background image accordingly for mobile devices. Afterwards, accessibility became a bit of a problem. I was struggling with finding semantically correct HTML tags for the inserted and deleted prices. Eventually, after some research I discovered the <ins> and <del> both of which I never knew existed before this project.
 
### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

How to provide accessbility as well as using semantically correct HTML tags that indicate deleted or inserted text.

### Continued development

Accessibility is something I am really lacking. For the most part I understand the overall structure and flow of a semantically correct HTML document (there may be some research needed for some odd tags that I don't use that often), however I'm far from perfect on it and it is a skill I need to further improve.

*
### Useful resources

- [<ins> documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ins#:~:text=The%20HTML%20element%20represents,been%20deleted%20from%20the%20document.) - Helped me understand <ins> tags.
- [<del> documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/del#:~:text=The%20HTML%20element%20represents,been%20added%20to%20the%20document.) - Helped me understand <del> tags.
- [accessibility documentation] (https://www.w3.org/TR/wai-aria-1.2/#generic) - Provided more information on accessibility

## Author

- Website - [Carlos Arbizu](https://arbizu.dev/)
- Frontend Mentor - [@crypto-dot](https://www.frontendmentor.io/profile/crypto-dot)


