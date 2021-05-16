<h2 align="center">Frontend Mentor - Stats preview card component</h2>

[![Netlify Status](https://api.netlify.com/api/v1/badges/5694d0ca-05cc-4784-b4c9-26a18ae3e113/deploy-status)](https://app.netlify.com/sites/stats-preview-card-evavic44/deploys)

## Welcome! 👋
This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](###overview)
  - [The challenge](###the-challenge)
  - [Screenshot](###screenshot)
  - [Links](###links)
- [My process](###my-process)
  - [Built with](###built-with)
  - [What I learned](###what-i-learned)
  - [Continued development](###continued-development)
  - [Useful resources](###useful-resources)
- [Author](###author)
- [Acknowledgments](###acknowledgments)

### Overview

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

<img src="https://user-images.githubusercontent.com/62628408/118215538-94720c00-b469-11eb-8e53-63816db7738a.png" width="500px">


### Links

- Solution URL: [GitHub](https://github.com/Evavic44)
- Live Site URL: [Live](https://stats-preview-card-evavic44.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS3 styling
- No frameworks or programming language was used. Just plain old HTML, CSS

### What I learned
<h4>Building this project has helped me to fortify my CSS skills in the following departments</h4>

- Alignment: This is one of the issues I struggled with. After adding the flex property to the column classes, the card box was too spaced out and elements shrinked on smaller screens, by adding the `max-width` and ```margin: 0 auto;``` property, the text properly aligned to the container. _This might help if you plan on taking this challenge_

### Code Snippets
I added the provided color code pallete to a var property as seen below. This pallete was really helpful to me _adding it to a variable for easy reference is highly recommended_.

```css
:root {
  --main-background: hsl(233, 47%, 7%);
  --card-background: hsl(244, 38%, 16%);
  --accent: hsl(277, 64%, 61%);
  --main-heading: hsl(0, 0%, 100%);
  --text-secondary: hsla(0, 0%, 100%, 0.75);
  --text-secondary-card: hsla(0, 0%, 100%, 0.6);
}
```


Since the font family link was gracefully provided by [Frontend Mentor](https://www.frontendmentor.io) on google fonts, I added it to the `css` easily using the css import property. _Do check it out for adding the fonts easily [here](https://fonts.google.com/specimen/Inter?query=inter)_
```css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Lexend+Deca&display=swap');
```

### Continued development
Going forward, I would like to improve on my `CSS` skills -primarily on Alignment and Positioning. WHY!? well because I'm not quite satisfied with the length of `CSS` code I wrote to achieve this owing that to the alignment sections of this challenge.   

### Useful resources

- [Cooolors](https://www.cooolors.co) - This helped me to generate and convert the `HSL` css color codes to `HEX` which I'm probably more used to.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

### Author

- Website - [Victor Eke](https://www.your-site.com)
- Frontend Mentor - [@evavic44](https://www.frontendmentor.io/profile/evavic44)
- Twitter - [@evavic44](https://www.twitter.com/evavic44)

### Acknowledgments

Credit goes to the team at [Frontend Mentor](https://www.frontendmentor.io) for putting out this challenge freely. You all ROCK! 💎 
