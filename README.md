# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./assets/images/screenshot.PNG)

### Links

- Solution URL: [Frontendmentor](https://www.frontendmentor.io/solutions/product-preview-card-component-LLCf8wjyko)
- Live Site URL: [Github](https://github.com/TheRoboRobin/Frontend-Mentor-Product-Preview-Card)

## My process

It took me quite a while to figure out how to properly deploy and build the website for submission this time. Using sass created an issue by the fact my index wasn't in the root folder.

First attempt was trying to rename public to docs. This didn't really work and created a huge mess. I ended up deleting and rebuilding the repository.

Then I read around about Hugo. I couldn't get hugo to work how I wanted it to and so I eventually scrapped that.

Finally after some more reading, I ended up altering the static html template for deployment from the public folder. This worked. Finally.

I can see how this is going to become more complicated as my pages become larger.

I built out things as normal. Outline, build html, then style. Everything was largely okay. Missed how I had named one class. So when I was trying to style the button icon in my nested css, it wasn't working. But I had just misnamed it. Proceeded as normal after that.

I came back at this point to make it so different images were served based on the screen size. The issue was that I was having trouble remembering which version to use. And for a bit I was trying to do resolution switching instead of art direction. But once I caught that mistake, I figured it out quickly. Lots of absent minded mistakes today.

My brain got scrambled a bit doing the media queries the other way with the mobile first but I got there eventually.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Dart Sass
- GitHub Workflows

### What I learned

The biggest thing I learned was how to create an action for github. It came very much in handy to make it so that it automatically creates the page from the public folder instead of the source.

### Continued development

Now that I've completed one project doing it, I hope that next time will be easier. I also want to continue to work on learning more about GitHub Workflows.

### Useful resources

- [Daniel Jimenez Garcia](https://medium.com/@danieljimgarcia/publishing-static-sites-to-github-pages-using-github-actions-8040f57dfeaf) - Used to read up on the static site deployment actions.
- GitHub's Static HTML Template
- My package.json and project structure is adapted from [Stephanie Eckles](https://thinkdobecreate.com/articles/minimum-static-site-sass-setup/)'s article on the setup.

## Author

- Website - [Robin](https://github.com/TheRoboRobin)
- Frontend Mentor - [@TheRoboRobin](https://www.frontendmentor.io/profile/TheRoboRobin)
