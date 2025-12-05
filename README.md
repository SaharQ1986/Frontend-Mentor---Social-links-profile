# Frontend Mentor - Social links profile

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Layout Structure](#Layout-Structure)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## 🧠 Overview

### 🔹 The Challenge

Users should be able to:

- View the component on mobile and desktop sizes
- See hover and focus states for all interactive elements (desktop)
- Read the profile information clearly
- Navigate the social link buttons with correct styling

### Screenshot

![](design/mobile-design.jpg)

### Links

- Solution URL: [URL solution](https://github.com/SaharQ1986/Frontend-Mentor---Social-links-profile.git)
- Live Site URL: [live site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

## 🧠 What I Learned

This challenge helped reinforce:

- Structuring simple UI components with semantic HTML
- Managing vertical spacing using Flexbox
- Applying a mobile-first responsive design approach
- Using custom CSS variables for color and typography
- Implementing hover/focus states cleanly and accessibly

To see how you can add code snippets, see below:

```css
@media (min-width: 1200px) {
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
  }
  .social-links a:hover {
    cursor: pointer;
    color: var(--clr-gray-800);
    background-color: var(--clr-green);
  }
}
```

---

## 🧱 Layout Structure

The project is composed of:

- A centered card wrapper
- A profile section (image + name + location + bio)
- A list of social links
- A dark background layout optimized for all screen sizes

## Author

- Frontend Mentor – [@SaharQ1986](https://www.frontendmentor.io/profile/SaharQ1986)
- GitHub – [@SaharQ1986](https://github.com/SaharQ1986/Frontend-Mentor---Social-links-profile.git)

## Acknowledgments

Design concept inspired by [Frontend Mentor](https://www.frontendmentor.io/).
