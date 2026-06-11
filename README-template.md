# Frontend Mentor - Social Links Profile Solution

This is my solution to the Social Links Profile challenge on Frontend Mentor. The goal of this project was to recreate the provided design using semantic HTML and CSS while ensuring proper hover states and responsive behavior.

## Overview

### The Challenge

Users should be able to:

* View the profile card centered on the page
* See hover states for all social link buttons
* Experience a responsive layout across different screen sizes

### Screenshot

![Project Screenshot](./assets/images/Screenshot%202026-06-11%20190246.png)

### Links

* Solution URL:[Sol](https://github.com/Jaydip-gharat/FM-Social-links-profile)
* Live Site URL:[live url](https://jd-social-link-profile.netlify.app/)

## My Process

### Built With

* Semantic HTML5
* CSS Custom Properties
* Flexbox
* Local Font Loading with `@font-face`
* Mobile-First Workflow

### What I Learned

During this project, I practiced:

* Structuring content with semantic HTML elements such as `main` and `article`
* Using CSS variables to manage colors efficiently
* Centering elements with Flexbox
* Creating hover effects using the `:hover` pseudo-class
* Loading custom fonts from local files with `@font-face`

Example of the hover effect used:

```css
.containers:hover {
    background-color: var(--Green);
    color: var(--Grey-900);
    cursor: pointer;
}
```

### Continued Development

In future projects, I would like to focus on:

* Improving accessibility by using anchor (`<a>`) elements for social links
* Creating more responsive layouts with `clamp()`, `min()`, and `max()`
* Writing cleaner and more scalable CSS
* Learning CSS Grid in greater depth

### Useful Resources

* Frontend Mentor Community
* MDN Web Docs
* CSS Tricks Flexbox Guide

### AI Collaboration

For this project, I used ChatGPT to:

* Review my HTML and CSS structure
* Get feedback on code quality and responsiveness
* Learn better semantic HTML practices
* Understand when to use Flexbox and responsive sizing techniques

The AI was most helpful for code reviews and identifying areas for improvement while still allowing me to build the solution myself.

## Author

* Frontend Mentor - [@jaydip-gharat](https://www.frontendmentor.io/profile/Jaydip-gharat)
* GitHub - [@jaydip-gharat](https://github.com/Jaydip-gharat)

## Acknowledgments

Thanks to the Frontend Mentor community for providing feedback and inspiration throughout the learning process.
