# Frontend Mentor - Testimonials grid section

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Welcome! 

Thanks for checking this out.

Here’s a clean, **ready-to-drop README** tailored to *your actual code* and the Frontend Mentor **Testimonials Grid Section** challenge. No filler, no fake tools, just honest and clear.

---

# Frontend Mentor – Testimonials Grid Section Solution

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
* [Author](#author)

---

## Overview

### The challenge

Users should be able to:

* View the optimal layout depending on their device’s screen size
* Clearly read testimonial content across different background colors
* Experience a responsive, mobile-first grid layout

This project focuses on layout structure, spacing, and visual hierarchy using CSS Grid.

### Links

* Live Site URL: [Live Demo](https://your-live-site-url.com)

---

## My process

### Built with

* Semantic HTML5
* SCSS (variables & nesting)
* CSS Grid
* Mobile-first workflow
* Google Fonts (Barlow Semi Condensed)

---

### What I learned

* How to structure a grid-based layout using **CSS Grid** with consistent gaps
* Using **SCSS variables** to manage colors and maintain design consistency
* Nesting styles in SCSS to keep component styles organized
* Handling light and dark cards while maintaining text readability

Example from this project:

```scss
.main {
  display: grid;
  border-radius: 10px;
  overflow: hidden;

  & .profile-section {
    display: grid;
    grid-template-columns: 65px 1fr;
  }
}
```

---

### Continued development

* Improve grid responsiveness for larger screens
* Refactor repeated styles into reusable SCSS mixins
* Experiment more with layout variations using `grid-template-areas`

---

## Author

* Frontend Mentor – [@vipzy](https://www.frontendmentor.io/profile/vipzy)
* Linkedin – [Awosanya Ifeoluwa](https://linkedin.com/awosanyaifeoluwa)


