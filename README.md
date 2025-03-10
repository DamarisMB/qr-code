# Frontend Mentor - QR code component

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

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- This project really put my knowledge to the test. I researched when I would get stuck.
-

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I found it fun and challanging as a beginner to figure out the container height to replicate the end result. Originally I started with height: 400px and the container was smaller than the QR code card. Instead of a fixed height, updated code to min-height and that increased the container size.
Started off with:

````css
.container {
  width: 90%;
  max-width: 900px;
  height: 400px;
}
&modifiedto: ```css .container {
  width: 90%;
  max-width: 900px;
  min-height: 60vh;
}
````

### Continued development

Flex-box is still an area I need practice with. I will continue to build projects to help me get more comfortable with it.

### Useful resources

- [ mdn\_ ](https://developer.mozilla.org/en-US/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.


**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Damaris Barajas](https://www.your-site.com)
- Frontend Mentor - [@DamarisMB](https://www.frontendmentor.io/profile/DamarisMB)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**