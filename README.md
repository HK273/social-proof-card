# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Table of contents

- [Links](#links)
- [Code Snippets](#my-process)
- [Useful resources](#useful-resources)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/four-card-section-grid-flexbox-responsive-3LySr1LRe)
- [Live Site URL](https://hk273.github.io/four-card-section/)


### Code Snippets


```css
/* Little zoom effect on card hover */

.item:hover {
    cursor: pointer;
    opacity: 0.6;
    transition: transform .2s;
    transform: scale(1.02);
}

```
```css
/* Grid to two equal columns / rows */

@media (max-width: 1000px) {
    .container {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }
}

/* Grid set up for card layout */
.container {
    display: grid;
    grid-gap: 3rem;
    /* Allows for more responsiveness */
    grid-template-columns: repeat(auto-fit, minmax(34.4rem, 1fr));
    grid-auto-flow: dense;
    /* grid-template-columns: 34.6rem 34.6rem 34.6rem; */
    justify-content: center;
    margin: 5rem 10rem;
}

/* Moving item in gird */
.item4 {
    border-top: 0.6rem solid var(--orange);
    grid-column-start: 2;
}
  
   
```


### Useful resources

- [Centre Items](https://css-tricks.com/centering-in-css/)
- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#background)
- [Grid](https://thoughtbot.com/blog/positioning#grid) 
- [Controlling line breaks](https://stackoverflow.com/questions/7596647/ignore-br-with-css) 
- [Markdown Live Preview](https://markdownlivepreview.com) 



