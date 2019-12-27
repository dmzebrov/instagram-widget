# Instagram widget for pages
The best responsive Instagram widget for websites absolutely free! You can fetch your last 12 Instagram photos without the usage of Instagram API, which requires a user to authenticate.

[Demo](https://jakubskowronski.com/instagram-widget)

## Requirements:
- [Axios](https://github.com/axios/axios#installing)

## How to use:
Add required files in your site header as like as bellow:

```html
<link href="/src/instagram-widget.min.css" rel="stylesheet">
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script src="/src/instagram-widget.min.js"></script>
```

Embed the code below wherever you want the widget to be displayed:

```html
<div data-username="instagram"
     data-header="yes"
     data-width="80vw"
     data-columns="4"
     data-color="#3897f0">
</div>
```