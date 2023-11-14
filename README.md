# Laguna Brava Ecotourism Website

This website promotes activities offered by the communities settled around the lake Laguna Brava in western Guatemala.

This website is based on the [Grayscale](https://startbootstrap.com/theme/grayscale) template from [Start Bootstrap](https://startbootstrap.com/).

Links:
- [Website published on GitHub Pages](https://josecarlosgt.github.io/Laguna-Brava/header-image-optimized/index.html)
- [Google Lighthouse Report (Desktop)](https://googlechrome.github.io/lighthouse/viewer/?gist=c542a7d8164c482972dbbb36de5615c2)
- [Google Lighthouse Report (Mobile)](https://googlechrome.github.io/lighthouse/viewer/?gist=5db5ae4337a717ab8a9b2cb809a80aba)

### Full-height header image

The webpage above shows a full-height image on its header. Websites commonly use an image as a background that occupies the full height of the screen on their homepage to deliver an impactful first impression to their users. You can create a full-height header image by specifying a few properties that affect the background settings of an HTML element, such as a div or header element. For example: 

```css
header {
  background: url("../assets/img/panoramic-laguna-brava.webp") no-repeat center center fixed;
  background-size: cover;
  height: 100%;
  overflow: hidden;
}
```

> These properties specify an image as the background of the header element. Notice the image's URL is specified in the stylesheet, not the HTML. Thus, the path to the image is relative to the CSS file.

```html
<header>
  ...
</header>
```

Source:  [CSS-Tricks: Full-Page Background Image](https://css-tricks.com/perfect-full-page-background-image/)
