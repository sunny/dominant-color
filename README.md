# Dominant Color

WordPress plugin to save the dominant color of the image file you upload.

Also adds a metabox with a colorpicker in your Media library.


## Installation

1. Upload the plugin in your `wp-content/plugins` directory
2. Activate it on the plugin administration page


## Usage

Call the hexadecimal code in your template, for example:

``` php
$meta = get_post_meta( $post->ID, 'dominant_color', true );
$color = (empty($meta)) ? $color : $meta;
```
