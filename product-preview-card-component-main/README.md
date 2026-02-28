## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [AI Collaboration](#ai-collaboration)
  - [Author](#author)

## Overview

This is my solution to the [Product Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). The goal was to build a responsive product card that adapts its layout and imagery between mobile and desktop viewports, closely matching the provided design.

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the product image switch between a portrait (mobile) and landscape (desktop) version using `<picture>` and `<source>` for art direction
- See hover and focus states for the interactive **Add to Cart** button

### Screenshot

![](./assets/images/screenshot.png)

### Links

- Solution URL: [Repository](https://github.com/joaogllm/frontend-mentor-tests/tree/main/results-summary-component-main)
- Live Site URL: [Live](https://joaogllm.github.io/frontend-mentor-tests/results-summary-component-main/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first responsive design

### AI Collaboration

This challenge was completed with the assistance of [Claude](https://claude.ai) (Anthropic) as a learning and code review tool.

Claude was used to:

- Generate a **mobile-first CSS reset** as a starting base
- **Review my HTML and CSS** after my initial implementation and point out areas for improvement — including semantic misuse of heading elements, unnecessary `<section>` tags, and CSS organisation
- **Diagnose the desktop image issue** I was having, where the product image wasn't stretching to fill the card's full height. The fix involved setting `height: 100%` on the `<picture>` element and using `object-fit: cover` on the `<img>` tag

All final implementation decisions, code writing, and design matching were done by me. AI was used strictly as a reviewer and explainer, not as a code generator.

## Author

- Instagram - [Joao Martins](https://www.instagram.com/joaogllm/)
- Frontend Mentor - [@joaogllm](https://www.frontendmentor.io/profile/joaogllm)
- Github - [@joaogllm](https://github.com/joaogllm)
