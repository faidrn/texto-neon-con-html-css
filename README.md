# Neon text with HTML and CSS

![](https://github.com/faidrn/texto-neon-con-html-css/blob/main/assets/images/ScreenShotDigitalClock.png)


Neon text with HTML and CSS.

## HTML

This HTML defines a basic structure containing a title with a neon text effect.

```html
<div class="container">
    <h1 class="neon-text">Ne&oacute;n</h1>
</div>
```

* **<div>**: We define a block element in HTML that acts as a container. It is commonly used to group other elements and apply styles to them together.

* **class="container"**: We add the container class to the div. In HTML, classes are used to apply specific CSS styles to elements.

* **<h1>**: We define a level 1 heading, which is generally used for main titles.

* **class="neon-text"**: We add the neon-text class to the **<h1>** element. This class will be used to apply specific CSS styles that create the neon text effect.

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

* 