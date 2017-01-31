# uqlibrary-carousel

[![Dependency Status](https://david-dm.org/uqlibrary/uqlibrary-carousel.svg)](https://david-dm.org/uqlibrary/uqlibrary-carousel)
[![Dev Dependency Status](https://david-dm.org/uqlibrary/uqlibrary-carousel/dev-status.svg)](https://david-dm.org/uqlibrary/uqlibrary-carousel?type=dev)

A simple, responsive, image slider (carousel) built and designed for Polymer. Only dependencies are Polymer elements.

## Demo

For a demo and full property rundown see [GH Pages](http://uqlibrary.github.io/uqlibrary-carousel).

## Usage
```sh
bower install uqlibrary/uqlibrary-carousel --save
```
- Add images via JS
```sh
HTMLImports.whenReady(function () {
    var carousel = document.querySelector('uqlibrary-carousel');
    carousel.slides = [
        {
            link: "http://library.uq.edu.au/",
            image: {
                href: "http://lorempixel.com/800/300/abstract",
                description: "Test image"
            }
        }
    ]
});
```

## Options
For a full list of options see [GH Pages](http://uqlibrary.github.io/uqlibrary-carousel)

## Browser Support
- IE9+
- Chrome ~
- Firefox ~
- Safari ~
