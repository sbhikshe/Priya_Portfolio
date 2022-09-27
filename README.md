# 02 Portfolio

## Table of Contents
* [Description](#description)
* [Wireframe](#wireframe)
* [Screenshot](#screenshot)
* [Code Snippets](#code-snippets)
* [Credits](#credits)
* [Author Links](#author-links)

***

## Description
This is my personal Portfolio developed using HTML and CSS. The page uses Flex and Grid CSS features as well as semantic HTML elements. The page is responsive to changes in screen size between various devices. The page has been deployed to the Github Pages at [Portfolio](https://sbhikshe.github.io/Priya_Portfolio/)

## Wireframe
\
!["Wireframe"](./assets/images/Portfolio%20Wireframe.png)
> **Note**: This layout is designed to be responsive to changes in device screen sizes. 
\
## Screenshot
\
!["Portfolio Screenshot"](./assets/images/Portfolio%20Screenshot.png)
\
 [Live Page](https://sbhikshe.github.io/Priya_Portfolio/)
***

## Code Snippets
### *1. Nav bars for header (topics) and footer (contact info) are set out as flex*
```
header nav,
footer nav {
    background-color: var(--headerfooter-bgcolor);
    padding: 10px;

    font-size: 125%;

    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
```
### *2. Each topic is a one row grid with Caption, yellow line and content*
```
.Topic {
    display: grid;
    grid-template-columns: 20% 10% 65%;
    padding: 1%;
}  
```
### *3. The projects (images) are laid out in a 3x3 grid*
```
#WorkProjects {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    column-gap: 1%;
}
.WorkProjectItem:nth-child(1) {
    grid-column: 1 / 3;
    grid-row: 1 / 3;
}
.WorkProjectItem:nth-child(2) {
    grid-column: 1 / 2;
    grid-row-end: 3 / 4;
}
.WorkProjectItem:nth-child(3) {
    grid-column: 2 / 3;
    grid-row-end: 3 / 4;
}
```
### *4. CSS variables, pseudo classes, linear gradient for background used.*    


***

## Credits
[A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)\
[Flexbox - Mozilla](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox#horizontal_and_vertical_alignment)\
[Basic concepts of Grid layout - Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout)\
[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Author Links
[LinkedIn](https://www.linkedin.com/in/sripriya-bhikshesvaran-8520992/)\
[Github](https://github.com/sbhikshe)
