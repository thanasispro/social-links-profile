# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: https://github.com/thanasispro/social-links-profile
- Live Site URL: https://thanasispro.github.io/social-links-profile/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Accessibility best practices
- Mobile-first workflow

### What I learned

One of the key areas I focused on in this project was improving accessibility for buttons. I ensured that all buttons have proper ARIA attributes, keyboard focus states, and meaningful labels for screen readers. Here's an example:

```html
<button aria-label="Follow on Twitter">
  <svg aria-hidden="true" focusable="false" width="24" height="24">
    <!-- SVG content -->
  </svg>
</button>
```

In this example:
- The `aria-label` provides a meaningful description for screen readers.
- The `aria-hidden="true"` ensures that the SVG is ignored by assistive technologies.
- The `focusable="false"` prevents the SVG from being focusable, improving keyboard navigation.

This approach ensures that the buttons are accessible to all users, including those relying on assistive technologies.

## Author

- Frontend Mentor - [@thanasispro](https://www.frontendmentor.io/profile/thanasispro)