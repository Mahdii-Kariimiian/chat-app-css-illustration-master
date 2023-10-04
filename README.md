Chat app CSS Illustration master

Junior challenge at frontendmentors.io 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I used](#what-i-learned)
- [Author](#author)

## Overview
This app is a challenge to test my CSS skills by making a detailed chat page.

### Screenshot


### Links
-Netlify: https://serene-gaufre-312b76.netlify.app/
- frontendmentors : https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I used

Here is a glimpse of what I used to build this mini project.
````


.whole {
    flex-direction: row;
    min-height: 100vh;
    align-items: center;
    justify-content: center;
    gap: initial;
    margin-right: 130px;
    gap: 150px;
  }

  .whole  > * {
    margin-inline: 0;
  }

  .whole::after {
    left: -150px;
    height: 90%;
    width: 550px;
    border-radius: 0 0 400px 400px;
  
  }
  .whole::before {
    content: '';
    position: absolute;
    background-color: rgba(245, 245, 245, 0.47);
    right: -175px;
    bottom: 0;
    height: 90%;
    width: 600px;
    border-radius: 300px 300px 0 0;
    z-index: -1;
  }
````
## Author
Mahdi Karimian
- linkedin (www.linkedin.com/in/mahdi-karimian-116643273)
- Frontend Mentor – @Mahdii-Kariimiian (https://www.frontendmentor.io/profile/Mahdii-Kariimiian)


