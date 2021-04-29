# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop view](/images/Desktop-view.png)
![Mobile view](/images/Mobile-view.png)

### Links

- Solution URL: [Github](https://github.com/atulanand206/fem-stats-preview-card)
- Live Site URL: [Netlify](https://fem-stats-preview-card.netlify.app/)

## My process

- Started off with the HTML DOM hierarchy and added divs with class names to all the components. 
- The stats looked similar, hence I chose to create reusable classes for those.
- Added the colors, fonts and dimensions in the `:root` CSS tag to have a fixed number of variables to work with. The names could use some work.
- Assigned margin and padding of 0 to all the relevant tags.
- The crude UI was ready with fonts and color.
- Realized that there are only a small set of types of text to work with and h* tags can be used with proper font scaling using em. Removed all the classes that I could.
- A few divs remained and they were surely to be flex containers.
- The mobile version started looking great from what I thought of in the beginning in an hour or so.
- Fixed the footer positioning before moving onto the desktop version.
- Had to figure out about media queries but eventually worked that out.
- The image is too troublesome of a component and it's breaking at several different resolutions, looking stretched and shrinked and all over the place. 
- Struggling with the purple overlay.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Firefox dev tools

### What I learned

- HTML5 markup is powerful and can be easily used to differentiate between components against divs.
- Fonts can be imported swiftly.
- Stay cautious while naming CSS custom properties.
- Initializing margin and padding as 0 can go a long way in streamlining the behaviour.
- Media queries override certain attributes without much of a hassle.

### Continued development

- Image placement and sizing.
- Container variations.

### Questions for clarification

- How to work with img sizing? As the image does not scale like text does, it becomes hard to manage its responsiveness. How to make it so that img also scales relatively?

## Author

- Atul Anand

## Acknowledgments

Thanks to [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) for the focused YT tutorials.

## Submitting your solution

Submit your solution on the platform for the rest of the community to see. Follow our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) for tips on how to do this.

Remember, if you're looking for feedback on your solution, be sure to ask questions when submitting it. The more specific and detailed you are with your questions, the higher the chance you'll get valuable feedback from the community.