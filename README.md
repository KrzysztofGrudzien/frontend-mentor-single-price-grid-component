# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Single price grid component solution](#frontend-mentor---single-price-grid-component-solution)
  - [Table of contents](#table-of-contents)
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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/KrzysztofGrudzien/frontend-mentor-single-price-grid-component](https://github.com/KrzysztofGrudzien/frontend-mentor-single-price-grid-component)
- Live Site URL: [https://krzysztofgrudzien.github.io/frontend-mentor-single-price-grid-component/](https://krzysztofgrudzien.github.io/frontend-mentor-single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bem Methodology
- Mobile-first workflow

### What I learned
How to create very easy price component based on Figma layout.

```html
<div class="container">
    <div class="subscription">
        <h2 class="subscription__title">Monthly Subscription</h2>
        <div class="subscription__price"><span>&dollar;29</span> per month</div>
        <p class="subscription__description">Full access for less than &dollar;1 a day</p>
        <a href="" class="subscription__link">Sign Up</a>
    </div>
    <article class="about">
        <h2 class="about__title">Why Us</h2>
        <ul class="about__list">
            <li class="about__list-item">Tutorials by industry experts</li>
            <li class="about__list-item">Peer &amp; expert code review</li>
            <li class="about__list-item">Coding exercises</li>
            <li class="about__list-item">Access to our GitHub repos</li>
            <li class="about__list-item">Community forum</li>
            <li class="about__list-item">Flashcard decks</li>
            <li class="about__list-item">New videos every week</li>
        </ul>
    </article>
</div>
```
```css
.subscription__link {
    align-items: center;
    background-color: var(--color-secondary);
    box-shadow: 0 10px 10px hsla(0, 0%, 0%, 0.1);
    border-radius: var(--radius-5);
    color: var(--color-text-light);
    display: flex;
    justify-content: center;
    font-size: 1.6rem;
    line-height: 4.8rem;
    transition: background 0.3s ease, color 0.3s ease;
}

.subscription__link:hover {
    background-color: var(--color-text-light);
    color: var(--color-primary);
}

.subscription__description {
    font-size: 1.6rem;
    padding: 0.8rem 0 3rem 0;
}


```

### Continued development

### Useful resources

## Author

- Website - [In progress]
- Frontend Mentor - [@KrzysztofGrudzien](https://www.frontendmentor.io/profile/KrzysztofGrudzien)
- E-mail - krzysztof.grudzien.fed@gmail.com


## Acknowledgments
