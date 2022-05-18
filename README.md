# Frontend Mentor - Intro section with dropdown navigation

![Design preview for the Intro section with dropdown navigation coding challenge](./design/desktop-preview.jpg)

# Frontend Mentor - Intro section with dropdown navigation solution

This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](solution.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- HTML
- CSS 
- Flexbox
- Vanilla JS

### What I learned

I learned so much on this project from how NOT to do a pull request (rest in peace my original repo) to how to properly contain an image in a div. This was my first junior level challenge on frontend mentor and I am so amazed I pulled it off! I gave myself 10 days to finish it and I was more or less done within 4 days! I could have uploaded it before but thats when I messed up a pull request that conflicted my Github files lol. So, the original repo is in the shadow realm now i guess. I dont have the know-how to fix it and tbh I dont really want to. It will be a relic of my mistakes that I can always look back on and remember. All in all I really really enjoyed this challenge.

```css
.dropdown-content {
  border-radius: 10px;
  min-height: 1em;
  margin-top: 1em;
  box-shadow: 0px 8px 16px 0px hsla(0, 0%, 0%, 0.315);
  z-index: 1;
  display: flex;
  flex-direction: column;
  overflow: hidden;
}

.dropdown-content a {
  color: hsl(0, 0%, 8%);
  padding: 1em;
  text-decoration: none;
  display: block;
}

.dropdown-content li {
    font-size: 1rem;
    padding: 0;
    width: 100%;
}

.drop-img {
    margin-right: 0.5em;
}

/* Change color of dropdown links on hover */

.dropdown-content a:hover {
    background-color: hsl(0, 0%, 85%);
  }

.dropdown-arrow {
  color: hsl(0, 0%, 41%);
  outline: none;
  background: none;
  border: none;
  cursor: pointer;
  transition: all 0.2s ease-out;
}

.dropdown-arrow:hover {
  color: hsl(0, 0%, 8%);
}

.dropdown-links {
  text-decoration: none;
  display: block;
  padding: 1em;
  color: hsl(0, 0%, 8%);
}

.dropdown-links:hover {
  background-color: hsl(0, 0%, 98%);
}
```

### Continued development

I really need to work on my image resizign. The first half of this project was pure hell resizing the image within the div. It just did not want to cooperate!
Secondly is my css positioning in general(as usual) I will just keep working on it.
Lastly is javascript i honetsly didnt even know what I was doing there. Forget about continuos development I need an introduction to it lol.


### Useful resources

- [Stackoverflow align-an-element-to-bottom-with-flexbox](https://stackoverflow.com/questions/31000885/align-an-element-to-bottom-with-flexbox) - This helped me know how to use margin auto a lot better especially for positioning items within flex.

- [MND Docs object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) - The documentation on object fit helped me understand how to resize images in divs.

- [SVG images W3schools](https://www.w3schools.com/graphics/svg_intro.asp) - [SVG images W3schools](https://developer.mozilla.org/en-US/docs/Web/SVG) - These two sites helped me understand SVG images better

 - [Stackoverflow main tag](https://stackoverflow.com/questions/44803962/main-tag-as-a-column-wrapper) - This helped me understand the main tag use in html

- [Stackoverflow main tag](https://stackoverflow.com/questions/25225682/difference-between-width100-and-width100vw) - I could understand  the differnce bewteen 100vw and 100% thanks to this resource.


## Author

- Frontend Mentor - [@shemjay](https://www.frontendmentor.io/profile/shemjay)
- Twitter - [@shemstack](https://www.twitter.com/shemstack)

## Acknowledgments

Thanks to Cesare Polonara for providing me with the correct javascript on stackoverflow when i asked for help! This may be the only reason I was able to complete this question.

