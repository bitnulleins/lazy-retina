<img src="https://ps.w.org/lazy-retina/assets/banner-1544x500.png?rev=983098" style="width:100%">

# Lazy Retina (no active support anymore)
Lazy load retina (high DPI) sized images for WordPress (Plugin)

![Downloads](https://img.shields.io/wordpress/plugin/dm/lazy-retina) ![Active installs](https://img.shields.io/wordpress/plugin/installs/lazy-retina) ![Rating](https://img.shields.io/wordpress/plugin/stars/lazy-retina) 

Fast Retina Images (Lazy Load) boost your website performance and reduce the traffic because images outside of viewport (visible part of web page) won’t be loaded until the user scrolls to them. This lazy technique works with jQuery or zepto.js.

Lazy Retina loads by default:
* thumbnails
* images in posts
* images in pages
* This plugin is based on Unveil.js.

*RETINA IMAGES: The Lazy Retina plugin automatically adds retina sizes to every (custom) image size. You’ve to regenerate already uploaded images.*

# Installation

Download lazy-retina.zip and upload it to your Wordpress.

# Support in themes

If you want to lazy load an image in themes please use the following code:
```
<?php if (function_exists('lazy_retina_image') { echo lazy_retina_image( $image_id, $size, $attr ); } ?>
```

# Settings

Under “Options” -> “Media” you can remove the default link to full image path

# Support

Since 09.01.2021 I don't maintain this plugin. Sorry.
