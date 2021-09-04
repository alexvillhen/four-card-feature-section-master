# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

The challenge is to build out this feature section and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![screenshot of the project](https://github.com/alexvillhen/four-card-feature-section-master/blob/main/Screenshot.png?raw=true)


### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile first
- Responsive for mobiles, tablets and computers


### What I learned

I choosed this project because I saw it as an opportunity to refresh my knowledge on Grid Layouts, it took me a while, but eventualy I managed to put every item where they should be.

```html
<div class="grid">
      <div class="supervisor container">
        <h3>Supervisor</h3>
        <p>Monitors activity to identify project roadblocks</p>
        <img src="images/icon-supervisor.svg" alt="mini-logo">
      </div>

      <div class="team container">
        <h3>Team Builder</h3>
        <p>Scans our talent network to create the optimal team for your project</p>
        <img src="images/icon-team-builder.svg" alt="mini-logo">
      </div>
      
      <div class="karma container">
        <h3>Karma</h3>
        <p>Regularly evaluates our talent to ensure quality</p>
        <img src="images/icon-karma.svg" alt="mini-logo">
      </div>

      <div class="calc container">
        <h3>Calculator</h3>
        <p>Uses data from past projects to provide better delivery estimates</p>
        <img src="images/icon-calculator.svg" alt="mini-logo">
      </div>
      
    </div>
```
```css
.grid{
    display:grid;
    grid-template-columns: 100%;
    grid-template-rows: 25%;
    gap:1.5em;
    margin-top:3em;
    text-align: left;
}

.grid .container{
    border-radius: 7px;
    box-shadow: 0px 4px 20px 0px #7a7a7a71;
    display: flex;
    flex-direction: column;
    padding:1em;
    max-width: 300px;
}
}
```


### Continued development

I'm aware that I have to keep practicing the use of Grid so I'll keep working on this kind of projects in the future to improve that.


## Author

- Website - [Alejandro Villaescusa](https://www.facebook.com/alejandro.villaescusahenriquez/)
- Frontend Mentor - [@alexvillhen](https://www.frontendmentor.io/profile/alexvillhen)
- Twitter - [@alexvillhen](https://www.twitter.com/alexvillhen)

