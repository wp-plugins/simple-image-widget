=== Simple Image Widget ===
Contributors: vickio
Donate link: http://vickio.net
Tags: image, sidebar, widget, photo, picture
Requires at least: 2.5
Tested up to: 3.0
Stable tag: 1.3

The simple way to place images in your sidebars.

== Description ==

Using this widget you can easily place an image in the sidebar. You can also specify a URL to link to when clicking on the image. Supports multiple instances, so you can use it multiple times in multiple sidebars.

Once the plugin is enabled, the widget will be available in your widgets list as "Simple Image". You can add this widget to sidebars as many times as you need. The control interface allows you to specify the following options for each instance of the widget:

* Image URL: The full URL to the image file
* Alternate Text: Shown by the browser if image cannot be displayed
* Link URL: URL to open when the image is clicked on (optional)
* Open link in new window: If this is checked, the above link URL will open in a new browser window

== Installation ==

Installation is very simple:

1. Copy/upload the `simple-image-widget` folder to your `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the "Simple Image" plugin to a sidebar in 'Design' -> 'Widgets'

== Frequently Asked Questions ==

= How do I upload an image? =

The Simple Image widget does not provide a mechanism for uploading images or files. You can however upload an image in the 'Write' section of Wordpress. From there you can click on the 'Add an Image' icon (next to 'Add Media' label). After uploading an image, copy the 'Link URL' for use in your Simple Image widget.

= How many images can be display? =

Each instance of the widget can only display one image, but you can create as many instances as you need.

= How do I remove the border from around a link image? =

In your theme's CSS file, add this code:

`.simpleimage img { border: 0px; }`

= How do I change the alignment of the images? =

This can also be done with CSS:

`.simpleimage { text-align: center; }`

== Screenshots ==

1. Simple Image Widget control interface
