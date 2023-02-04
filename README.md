# Frontend Mentor - Stats Preview Card Component (Solution)

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). <br>
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents:

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Notes](#notes)


## Overview:

### The challenge:

Users should be able to:
- View the optimal layout depending on their device's screen size
- Get it looking as close to the design as possible.

### Screenshot:

<div align="center"> 

| Original View | 
|---------|
| ![](design-finished/5.1-Original-20230204_150032.png) |

| Animated Preview | 
|---------|
| ![](design-finished/5.4-animatedResult.gif) |

<br>

**Note: I use 1 media query, so it only has 2 different view (Mobile & Desktop View)**
All viewports were included (except for the 4k view), in case the observer wishes to see the minor changes.

<br>

| Desktop View | Laptop View | Tablet View |
|---------|---------|---------|
| ![](design-finished/4.Desktop-20230204_145647.png) | ![](design-finished/3.Laptop-20230204_145736.png) | ![](design-finished/2.Tablet-20230204_145806.png) |

| Mobile Large | Mobile Small (iPhone SE) | iPhone 8+ (Safari Browser) | iPhone 8+ (Brave Browser) |
|---------|---------|---------|---------|
| ![](design-finished/1.MobileL-20230204_145902.png) | ![](design-finished/0.MobileS-20230204_145959.png) | ![](design-finished/5.2-iOS-safariBrowser.png) | ![](design-finished/5.3-iOS-braveBrowser.png)|

</div>

### Links:
- Live Site URL: [Website Link - Click Me](https://stats-prev-card-component.vercel.app/)
- Solution URL: [FrontEndMentor - Link](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-component-gUacH6GQFK)

## My process:

### Built with:
- HTML5
- CSS3

### What I learned:

Recap over some of the major learnings while working through this project:
- Basic review of HTML & CSS
- CSS Flex Layout (I've been a little bit better in using it)

<br>

This code snippets/function, is what **I'm proud to accomplished**:

```css
.ctn-overlay,
.ctn-img::after{
	position: absolute;
} 

.ctn-overlay, .ctn-img{
	width: 540px;
	height: 400px; /* Static size sort of solve the problem */
	margin: 0;
	position: relative; 
	background-color: hsla(277, 100%, 24.5%, 0.57); /* Starting now: I'll always use hsl/hsla in colors*/
	z-index: 2; 
}
```

<br>

This code snippets/function, is what **I struggled and took time to solve**:
- The responsiveness of image container (If you could see, I didn't use an img tag)
- The overlay of image container + responsiveness

```css
.ctn-img::after{
  content: '';
	background-size: cover;
	width: 100%;
	height: 100%;
  position: absolute;
	background: url(images.jpg) no-repeat center center;
} /* The hardest part was combining the overlay and image responsively*/
```


### Continued development:
<hr>

#### Here are a few possible areas that could be added or improved in the HTML and CSS code provided:
1. **Accessibility:** - It could be more accessible to users with disabilities by:
    - Include appropriate ARIA attributes, alt text, and semantic HTML tags. 
      - Some of the semantic tag that i forgot to use:
        - < header > 
        - Extra: Better use of < section >
2. **Responsiveness:** - Using responsive design techniques and media queries for different screen sizes and devices.
3. **Browser Compatibility:** - Not all browsers support the same features and rendering of web pages from the CSS styles I used.
4. **Cleaner Maintainable Code** - Not quite sure about this one, but I'm sure that there is a much better/cleaner approach to do what I did.

## Author:
- Github - [@Iron-Mark](https://github.com/Iron-Mark)
- Frontend Mentor - [@Iron-Mark](https://www.frontendmentor.io/profile/Iron-Mark)

## Acknowledgments:
- I would like to acknowledge the hard work and dedication that I went into creating this website. 
- I am grateful for my friends and to those who motivate me push through and not settle in relaxation. 
- I hope that this website serves its intended purpose. Thank you!

## Notes:
- I would be happy to recieve comments, criticism, and such that could improve the website:
  - Better way of doing this website
  - Cleaner Code
  - Better Practice/Approach of making this website.
- Feel free to approach and contact me :>
- _Finished Feb 4, 2022_