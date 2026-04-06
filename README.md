# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the social proof section depending on their device's screen size
- See responsive design that adapts from desktop (2-column grid layout) to mobile (single column layout)
- Access customer testimonials and 5-star ratings from verified buyers

### Screenshot

![Social Proof Section](./screenshot.jpg)

### Links

- Solution URL: [Social Proof Section on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA)
- Live Site URL: Available locally via index.html

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox layout
- CSS Grid layout
- Mobile-first responsive design
- League Spartan font family
- SVG background patterns

### What I learned

During this project, I reinforced my understanding of:

1. **CSS Grid with Flexbox** - Combining Grid for macro layouts and Flexbox for component-level alignment
2. **Responsive Design** - Creating mobile-first workflows that adapt from single-column to multi-column layouts
3. **BEM Naming Convention** - Using semantic class names following the Block Element Modifier pattern for maintainable CSS
4. **Semantic HTML** - Structuring content with meaningful HTML5 elements like `<section>` and `<aside>`
5. **CSS Media Queries** - Implementing breakpoints for optimal viewing across different screen sizes

Key code examples:

**Grid Layout:**

```css
.main__section {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
}
```

**Responsive Flexbox Component:**

```css
.section__rating {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  justify-content: center;
  gap: 20px;
}
```

**Semantic HTML Structure:**

```html
<section class="main__section">
  <aside class="main__section-aside">
    <h1 class="main__section-title">10,000+ of our users love our products.</h1>
  </aside>
  <section class="section__rating">
    <!-- Rating cards -->
  </section>
  <section class="section__comments">
    <!-- Customer testimonials -->
  </section>
</section>
```

### Continued development

Areas for future improvement and learning:

- **CSS Animations** - Add smooth transitions when testimonials load or on hover interactions
- **Accessibility** - Enhance keyboard navigation and ARIA labels for screen readers
- **Advanced Responsive Design** - Implement more granular breakpoints for tablet sizes (768px, 1024px)
- **Performance Optimization** - Optimize SVG background patterns and image sizes
- **Component Reusability** - Refactor CSS to create more reusable component patterns
- **JavaScript Interactivity** - Add dynamic filtering or sorting of testimonials

### Useful resources

- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - Comprehensive guide for understanding CSS Grid layouts and best practices
- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) - Detailed documentation on Flexbox properties and alignment
- [CSS-Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Practical examples and visual explanations of Grid concepts
- [Frontend Mentor](https://www.frontendmentor.io) - Platform providing realistic design-to-code challenges for skill development

### AI Collaboration

- **Tool Used:** GitHub Copilot
- **Usage:** Assisted with CSS refinement, debugging responsive layout issues, and optimizing component structure
- **What Worked Well:** Quick suggestions for Flexbox/Grid implementations and media query breakpoints
- **Experience:** Helpful for accelerating development while maintaining code quality and best practices

## Author

- Frontend Mentor - [@diego-quevedo](https://www.frontendmentor.io/profile/diego-quevedo)
- GitHub - [diego-quevedo](https://github.com/diego-quevedo)

## Acknowledgments

- Challenge provided by [Frontend Mentor](https://www.frontendmentor.io) - a platform that helped improve coding skills through realistic design-to-code projects
- Thanks to the open-source community for excellent CSS documentation and resources
