# Amazon-frontend-clone

This Readme file provides a comprehensive overview of the CSS stylesheet used in a web project. The stylesheet defines styles for various components, including the navigation bar, hero section, shop section, and footer. Each section of the code is explained in detail to help developers understand its purpose and functionality.

## General Styles
```css
*{
    margin : 0px;
    font-family: Arial;
    border: border-box;
}
```
- This code snippet sets default styles for all HTML elements, including margin, font family, and the box-sizing model.

## Navigation Bar
```css
.navbar{
    height: 60px;
    background-color: #0F1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
```
- The `.navbar` class styles the navigation bar, defining its height, background color, text color, and layout properties.

### Logo
```css
.nav-logo{
    height: 50px;
    width: 100px;
}

.logo{
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100%;
}
```
- These classes define styles for the logo within the navigation bar and another logo on the page. They set dimensions and background images.

### Borders
```css
.border{
    border : 1px solid transparent;
}

.border:hover{
    border: 1px solid white;
}
```
- The `.border` class defines a transparent border for elements, and on hover (`.border:hover`), it adds a white border. This creates a hover effect for elements with this class.

## Search Box
```css
.nav-search{
    display: flex;
    justify-content: space-evenly;
    background-color: aquamarine;
    width: 850px;
    height: 40px;
    border-radius: 5px;
}

.nav-search:hover{
    border: 2px solid #febd68;
}
```
- The `.nav-search` class styles the search box, setting its dimensions, background color, and border radius. It also defines a hover effect to add a border on mouse hover.

### Search Select Box and Input Field
```css
.search-select{
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border: none;
}

.search-input{
    width: 100%;
    font-size: 1rem;
    border: none;
}
```
- These classes style the select box and input field within the search box, setting dimensions, background color, and text alignment.

### Search Icon
```css
.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #febd68;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
```
- The `.search-icon` class styles the search icon, defining its size, alignment, and background color.

## Additional Elements
```css
.add-icon, .add-first, .add-sec, .nav-second, .nav-cart, .nav-cart i
```
- These classes are used for various elements within the navigation bar, providing styling for their text and icons.

## Panel
```css
.panel, .panel-ops, .panel-ops p, .panel-deals
```
- The `.panel` class styles a panel section on the webpage, including the options, text, and deals within it.

## Hero Section
```css
.hero-section{
    background-image: url("./hero_image.jpg");
    height: 380px;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
```
- The `.hero-section` class defines styles for the hero section, setting its background image, dimensions, and alignment.

## Shop Section
```css
.shop-section, .box, .box-img, .box-content p
```
- These classes are used for the shop section, including individual product boxes, product images, and product descriptions. They define dimensions, background colors, and text styles.

## Footer
```css
footer, .foot-panel1, .foot-panel2, ul, ul a, .foot-panel3, .logo, .foot-panel4, .pages, .copyright
```
- These classes define the styles for the footer section, which includes panels, lists, links, and logos.

## Conclusion
This CSS stylesheet provides comprehensive styles for a web project, allowing for customization and theming of various components. It covers the navigation bar, search box, hero section, shop section, and footer, making it a valuable resource for front-end development. Developers can easily integrate these styles into their web projects or adapt them to suit their specific design needs.
