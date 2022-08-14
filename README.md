# Frontend Mentor - Stats Preview Card

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
This is a task from Frontend Mentor to build a Stats Preview Card to aid my proficiency in learning CSS Grid.

### Screenshot

![](./images/Annotation%202022-08-14%20191017.png)

### Links

- Live Site URL:(https://peterforyou.github.io/Stats-preview-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt how to place the before selector on a given div element while trying to put opacity on an image and not disrupting the image.

```html
   <div class="box">    

   </div>
```
```css
 .box:last-child:before {
      content: '';
      background-color: hsl(277, 64%, 61%);
      position: absolute;
      opacity: 0.5;
      height: 100%;
      width: 100%;
      top: 0;
      left: 0;
      z-index: 1;
      border-bottom-right-radius: 3%;
      border-top-right-radius: 3%;
    }
```

### Continued development    

I would love to focus more on css animation, transition and transform properties to aid my proficiency in building eye catchy projects.

## Author

- Name - [Peter Bit](https://www.twitter.com/Peterbyte2)

## Acknowledgments

Am aknowledging my mentor [Adetutu Gbangbola](https://github.com/Adetutu777) for giving us this challenge to solve as this is a sharpener one to craft as a front end web developer.