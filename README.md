# Neon text with HTML and CSS

![](https://github.com/faidrn/texto-neon-con-html-css/blob/main/assets/images/ScreenShot.png)


Neon text with HTML and CSS.

## HTML

This HTML defines a basic structure containing a title with a neon text effect.

```html
<div class="container">
    <h1 class="neon-text">Ne&oacute;n</h1>
</div>
```

* `<div>`: We define a block element in HTML that acts as a container. It is commonly used to group other elements and apply styles to them together.

* `class="container"`: We add the container class to the div. In HTML, classes are used to apply specific CSS styles to elements.

* `<h1>`: We define a level 1 heading, which is generally used for main titles.

* `class="neon-text"`: We add the neon-text class to the `<h1>` element. This class will be used to apply specific CSS styles that create the neon text effect.

## CSS Styles - Neon Effect

With CSS we apply styles to create a visual effect of a text with a neon effect.

```css
body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #000;
    /*font-family: 'Arial', sans-serif;*/
    font-family: Arial, sans-serif;
}

.container{
    text-align: center;
}

.neon-text{
    font-size: 72px;
    color: #fff;
    text-shadow: 0 0 5px #00ffe4, 
            0 0 10px #00ffe4,
            0 0 20px #00ffe4,
            0 0 40px #00ffe4,
            0 0 80px #00ffe4,
            0 0 90px #00ffe4,
            0 0 100px #00ffe4,
            0 0 150px #00ffe4;
}
```

### Styles for the `body`:

* **display: flex**: Defines that the parent container (the body in this case) uses a flexible layout model, allowing easy arrangement and alignment of child elements.

* **justify-content: center**: horizontally centers child elements within the body.

* **align-items: center**: Vertically centers child elements within the body.

* **height: 100vh**: Sets the height of the body to 100% of the browser window height.

* **margin: 0**: Removes any default margin from the body, ensuring there is no white space around the content.

* **background-color: #000**: Sets the body background color to black (#000).

* **font-family: Arial, sans-serif**: Defines the font family to use for the body text. Try using Arial first, and if it's not available, use any sans-serif font.


### Styles for the class `.container`:

* **text-align: center**: horizontally centers child elements within the `.container` container


### Styles for the class `.neon-text`:

+ **font-size: 72px**: Sets the font size to 72 pixels for text inside .neon-text.

+ **color: #fff**: Sets the text color to white (#fff).

+ **text-shadow:**: Apply multiple shadows to text to create a neon effect:
    + **0 0 5px #00ffe4,**: First shadow with an offset of 0 pixels on the X and Y axes, a blur of 5 pixels and color #00ffe4.
    + **0 0 10px #00ffe4,**: Second shadow with a flur of 10 pixels.
    + **0 0 20px #00ffe4,**: Third shadow with a flur of 20 pixels.
    + **0 0 40px #00ffe4,**: Fourth shadow with a flur of 40 pixels.
    + **0 0 80px #00ffe4,**: Fifth shadow with a flur of 80 pixels.
    + **0 0 90px #00ffe4,**: Sixth shadow with a flur of 90 pixels.
    + **0 0 100px #00ffe4,**: Seventh shadow with a flur of 100 pixels.
    + **0 0 150px #00ffe4;**: Eighth shadow with a flur of 150 pixels.

These accumulated shadows create a glow effect that simulates neon text.