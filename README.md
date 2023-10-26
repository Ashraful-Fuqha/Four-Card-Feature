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

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS with gulpJS

### What I learned
I learned lot more on CSS3 and Specially Grid Property along that some of gulp concenpts and SASS.
see below:

```html
<section>
  <h3>Supervisor</h3>
  <p>Monitors activity to identify project roadblocks</p>
  <img src="./images/icon-supervisor.svg" alt="icon-supervisor">
</section>
```
```css
.cards{
    background-color: white;

    section:nth-child(1){
        border-top: 3px $cyan solid;
    }
    
    section:nth-child(2){
        border-top: 3px $red solid;
    }
    
    section:nth-child(3){
        border-top: 3px $orange solid;
    }
    
    section:nth-child(4){
        border-top: 3px $blue solid;
    }
}```
```gulpjs
function watchTask(){
    watch('index.html',browserSync.reload());
    watch([paths.stylesPath, paths.scriptPath],
    series(stylesTask,scriptsTask,browserSyncReload)
    );
}
```

### Continued development
Same as previous project.
## Author

- Website - I let you know
- Frontend Mentor - [@MjafarsadiqD](https://www.frontendmentor.io/profile/Ashraful-Fuqha)
