# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

Desktop

<img src="design/desktop-design.jpg" width="500px" >

Mobile

<img src="design/mobile-design.jpg" width="300px">
### Links

- Solution URL: (https://github.com/rug19/huddle-landing-page-with-curved-sections-master.git)
- Live Site URL: (https://rug19.github.io/huddle-landing-page-with-curved-sections-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to work with background position to form a wave image in the sections contents, I also learned media queries to leave the site responsive for mobile I didn't start with mobile first but I will test in my next project. Using media queries it's a simple way to adapt a site where the users can see the site in a mobile screen you can define the screen size and adpat all the contents for a better view.

```
@media (max-width:768px) {
  margin: 1rem 1.5rem;
    }

    .container-main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 1rem;
    }

    .title-head img {
        width: 8rem;
    }

{
```

### Useful resources

- [Rocketseat](https://youtu.be/H91DhKPjhPk) - This helped me with responsive layout. I really liked this pattern and will use it going forward. 


## Author
- Github - [rug19](https://github.com/rug19)
- Frontend Mentor - [@rug19](https://www.frontendmentor.io/profile/rug19)
