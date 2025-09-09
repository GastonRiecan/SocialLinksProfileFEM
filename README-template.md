# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/GastonRiecan/SocialLinksProfileFEM]
- Live Site URL: [https://social-links-profile-fem-nu.vercel.app/]

## My process

### Built with

- Semantic HTML5 markup
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- Flexbox
- Mobile-first workflow
- Custom color palette with Tailwind configuration

### What I learned

This project was an excellent opportunity to practice using Tailwind CSS with a custom color configuration. I implemented a complete design system using utility classes while maintaining clean, semantic HTML structure.

Key learnings include:

**Custom Tailwind Configuration:**
```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        'dark-bg': '#141414',
        'card-bg': '#1f1f1f',
        'lime-green': '#c4f82a',
        'button-bg': '#333333',
        'text-gray': '#999999'
      }
    }
  }
}
```

**Semantic HTML Structure:**
```html
<main class="w-full max-w-sm flex justify-center items-center">
  <article class="bg-card-bg rounded-xl px-8 py-10 text-center w-full shadow-2xl">
    <header class="mb-6">
      <!-- Profile content -->
    </header>
    <nav class="mt-6" aria-label="Social media links">
      <!-- Social links -->
    </nav>
  </article>
</main>
```

**Interactive Hover Effects:**
```html
<a href="#" class="block bg-button-bg text-white no-underline py-3 px-6 rounded-lg font-semibold text-sm transition-all duration-300 hover:bg-lime-green hover:text-dark-bg hover:-translate-y-0.5">
```

The project demonstrates how Tailwind CSS can create responsive, accessible designs with smooth animations and a cohesive color system, all while maintaining excellent performance through utility classes.
