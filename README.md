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
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

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

## Author

- Atul Anand

## Acknowledgments

Thanks to [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) for the focused YT tutorials.

## Deploying your project

As mentioned above, there are many ways to host your project for free. Our recommend hosts are:

- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)

You can host your site using one of these solutions or any of our other trusted providers. [Read more about our recommended and trusted hosts](https://medium.com/frontend-mentor/frontend-mentor-trusted-hosting-providers-bf000dfebe).

## Submitting your solution

Submit your solution on the platform for the rest of the community to see. Follow our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) for tips on how to do this.

Remember, if you're looking for feedback on your solution, be sure to ask questions when submitting it. The more specific and detailed you are with your questions, the higher the chance you'll get valuable feedback from the community.

## Sharing your solution

There are multiple places you can share your solution:

1. Share your solution page in the **#finished-projects** channel of the [Slack community](https://www.frontendmentor.io/slack). 
2. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor**, including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.
3. Share your solution on other social channels like LinkedIn.
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.
