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

![stats-previw-card-mobile](https://user-images.githubusercontent.com/90436675/159168740-a3f2db5d-bf15-4703-857d-2a39ead6683b.png)


Desktop

![stats-previw-card-desktop](https://user-images.githubusercontent.com/90436675/159168733-97d77b00-26fc-4885-a52a-2cbf83fa2898.png)

### Links

- Solution URL: https://github.com/Marvin-Erazo/stats-preview-card
- Live Site URL: https://stats-card-me.netlify.app/

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

