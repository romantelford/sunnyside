# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page


### Links

- Live Site URL: [https://romantelford.github.io/sunnyside/](https://romantelford.github.io/sunnyside/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I wanted to focus on readability and maintability of the code, so working with a certain folder layout and also naming conventions with divs etc.

```html
 <section id="intro">
            <div id="intro__card--transform" class="intro__card">
                <h2>
                    Transform your brand
                </h2>
                <p> We are a full-service creative agency specializing in helping brands grow fast. Engage your clients through compelling visuals that do most of the marketing for you.</p>
                <a class="intro__card--link">Learn more</a>
            </div>
            <div id="intro__card--transform--img" class="intro__card">
```

Same goes with using SCSS and focusing on the layout and structure of the SCSS file.

```css {
// ------------------------------------------ Colors
// ------------------------------------------ Primary
$underline_red: hsl(7, 99%, 70%);
$underline_yellow: hsl(51, 100%, 49%);
$graphicDesign_text: hsl(167, 40%, 24%);
$photography_text: hsl(198, 62%, 26%);
$footer_text: hsl(168, 34%, 41%);
$footer: #90d4c5;
$nav: #3dbeff;
// ------------------------------------------ Neutral
$grey_blue_400: hsl(212, 27%, 19%);
$grey_blue_300: hsl(213, 9%, 39%);
$grey_blue_200: hsl(232, 10%, 55%);
$grey_blue_100: hsl(210, 4%, 67%);
$grey_blue_50: #fffbf8;
$white: hsl(0, 0%, 100%
```
}
