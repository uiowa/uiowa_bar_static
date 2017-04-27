## Introduction

This repo provides assets to implement the [University of Iowa Branding Bar](https://brand.uiowa.edu/digital-templates) in web sites and applications. 

> If you are looking to implement the branding bar on a Drupal web site, you are encouraged to use the [uiowa_bar](https://github.com/uiowa/uiowa_bar) module.

### Example

You can see a live example of the branding bar at https://uiowa.github.io/uiowa_bar_static/

## Implementation

You can make a local copy of the uiowa-bar.css file and the appropriate png file for either the University or UIHC wordmark. You can then add the code found in the uiowa.html or uihc.html file to your site/application after the `<body>` tag or Skip to Content Link. Add the reference to the CSS file and update the source for the PNG file in the `<image>` tag in the `<svg>` tag.

You can also choose to include the javascript from the `<head>` tag in the example files if you want your site/app to be included with the University Google Analytics. This code will also allow you to automatically pick up other tags added to the University Tag Manager in the future.

If you want to change where the search box routes, you can update the `<form>` to point to a different location.
