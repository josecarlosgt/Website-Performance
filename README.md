# Laguna Brava Ecotourism Website

These websites promote activities offered by the communities settled around the lake Laguna Brava in western Guatemala.

## Header image

This website is based on the [Grayscale](https://startbootstrap.com/theme/grayscale) and [Small business](https://startbootstrap.com/template/small-business) templates from [Start Bootstrap](https://startbootstrap.com/).

### Full height header background image

Websites commonly use an image as background that occupies the full height of the header to deliver an impactful first impression to their users. 

Typically, you can create a full-height header background image by specifying a few properties that affect the background settings of an HTML element, typically a div or header element. For example, the Grayscale uses the following properties: 

```css
.masthead {
  ...
  background: url("../assets/img/panoramic-laguna-brava-2.jpeg");
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-size: cover;
}
```

```html
<header class="masthead">
  ...
</header>
```

> These properties essentially specify an image as the background of the header element. When customizing the Grayscale template, change the background property in the styles.css file to use an image of your choice. *Notice the path to the image is relative to the CSS file.*

### Multi-page website

Add pages to the website to organize the information maintained and offered by the website. 

Make sure all website pages are accessible through the site's navigation bar:

```html
  <ul class="navbar-nav ms-auto">
      <li class="nav-item"><a class="nav-link" href="index.html#activities">Activities</a></li>
      <li class="nav-item"><a class="nav-link" href="index.html#about">About</a></li>
      <li class="nav-item"><a class="nav-link" href="lake.html">The Lake</a></li>
      <li class="nav-item"><a class="nav-link" href="services.html">Services</a></li>
  </ul>
```

> Note all URLs in the anchor elements include the landing page to facilitate navigation between different pages. For example, a user can access the About section on the homepage from the Services page.

All pages on your website should follow the same style (e.g., font family and size are the same, buttons look the same, etc.) and share common sections, such as the header and footer.

Multi-page websites are often managed by Content Management Systems (CMS) or other systems that run on Web servers. For now, you may have to copy&paste the HTML markup that is common on all pages across your website.

Visit the website [here](https://josecarlosgt.github.io/Laguna-Brava/header-image).

## Header video 

This website is based on the [Grayscale](https://startbootstrap.com/theme/grayscale) template from [Start Bootstrap](https://startbootstrap.com/).

  This version of the Laguna Brava Ecotourism website uses a video as a background for the header section. The video is included using the HTML5 video tag:
  
```html
<video src="assets/video/introduction.mp4" autoplay loop playsinline muted></video>
```

Learn more about the \<video\> element [here](https://www.w3schools.com/html/html5_video.asp).

Visit the website [here](https://josecarlosgt.github.io/Laguna-Brava/header-video).
