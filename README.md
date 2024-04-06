# Social links profile

## Table of contents

- [Overview](#overview)
    - [The Challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My Process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
- [Acknowledgements](#acknowledgements)

## Overview

This is a solution to the [Social link profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

### The Challenge

This challenge is to build out social links profile.
Users should be able to see hover and focus states for all interactive elements on the page.

### Screenshot

![Screenshot](https://github.com/IrieBee/fem-social-links-profile/blob/main/images/screenshot.jpg)

### Links

* Solution URL: https://github.com/IrieBee/fem-social-links-profile
* Live Site URL: https://iriebee.github.io/fem-social-links-profile/

## My Process

### Built with

* Semantic HTML5 markup
* CSS custom properties

### What I learned

* `a:blank` will generate link with  `href:`,  `target="blank"` and  `rel="noopener noreferrer"`

* Move all the settings from `li` to `li a` so on hover effect will work when mouse touches the borders of the link not only the link itself. ***`display: block;`*** is very important.
```css
li a{
    display: block;
    background-color: var(--neutral-grey);
    padding: .875rem;
    margin: 1rem 0;
    border-radius: 0.5rem;
}
```


### Continued development

* Using emmet


## Acknowledgements

* [Odin project](https://www.theodinproject.com/)
* [Frontend Mentor](https://www.frontendmentor.io/home)