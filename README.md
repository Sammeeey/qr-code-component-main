# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![My solution for all screen sizes](./progress_documentation/all_screens_result.png)

<!-- Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.** -->

### Links

<!-- - Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com) -->

## My process

- Checkout the [LiveStreams on Twitch from 22th and 23th April 2022](twitch.tv/sammeeey/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Sass
<!-- - Flexbox
- CSS Grid -->
- Mobile-first workflow
<!-- - [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles -->

<!-- **Note: These are just examples. Delete this note and replace the list above with your own choices** -->

### What I learned

- basic practice and workflow with HTML and Sass for frontend design
  - derived from [Gary Simon's Crash Course](https://github.com/Sammeeey/HTML-CSS-CrashCourse-2021/)
- when to **not** work with media queries😅
- when to use absolute/relative scales

started design with relative width for QR card,
```
.card {
    max-width: 85vw;
}
```
which resulted in increasing card size on increasing screens.

Hence, switched to absolute scale:
```
.card {
    width: 318px;
}
```

<!-- Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
} 
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**
-->

### Continued development

- flexbox/grid -> positioning in CSS
- create good HTML skeleton for easy workflow with CSS
- UX design
  - figma/Adobe XD
- forms (also Django forms)
- Django
- Python
- JavaScript basics

<!-- Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.** -->
<!-- 
### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.** -->

## Author

<!-- - Website - [Add your name here](https://www.your-site.com) -->
<!-- - Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername) -->
- Twitter - [@CoderMatching](https://www.twitter.com/CoderMatching)
- Twitch - [Sammeeey](https://www.twitch.tv/sammeeey/)
- LinkedIn - [Samuel Hartmann](https://www.linkedin.com/in/samuel-hartmann-berlin)
<!-- 
**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.** -->

## Acknowledgments
<!-- 
This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.** -->

Great thanks to all the people who followed my process on Twitch or Twitter - even now in the beginning where I obviously still suck♥🤗