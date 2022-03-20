# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview
Stats preview card created with HTML and SASS

### Screenshot

Mobile 


Desktop


### Links

- Solution URL: https://github.com/Marvin-Erazo/stats-preview-card
- Live Site URL: 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex
- Mobile-first workflow
- [SASS] (https://sass-lang.com) - For stylesheet


### What I learned

Use html tags for the accesibility for example <main> or <footer> also i used rem dimensions for the letters
Flex direction to do a responsive desing, put the asides from left and rigth to top and bottom.
I used different dimmensions for the responsive desing and rrot elements in css for variables colors

```SCSS

main{
    .stats{
        display: flex;
        flex-direction: row-reverse;
}

//mobile L 425px

@media screen and (max-width: 426px) {
    main{
        height: max-content;

        .stats{
            flex-direction: column;
            text-align: center;
}
```
### Continued development

I will try use an css framework how bootstrap o talwind


## Author

- Website - [Marvin Erazo](https://marvin-erazo.github.io/)
- Frontend Mentor - [@Marvin-Erazo](https://www.frontendmentor.io/profile/Marvin-Erazo)
- GitHub - [Marvin-Erazo](https://github.com/Marvin-Erazo)

