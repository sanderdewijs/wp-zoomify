This plugin offers an easy way to embed zoomify .zif files in your WordPress website.

### Description

This Zoomify plugin for WordPress allows you to upload .zif files to your media directory. You can then create the Zoomify imagebox
with toolbar by using the shortcode [zoomify file="{fileUrl}" skin={Default/Dark/Light}], where {fileUrl} is the url/permalink to the zif-file.
The skin parameter has three options: Default, Dark and Light. If the skin parameter is omitted in the shortcode the Default skin will be used.

For example, if the permalink to your file is http://example.com/wp-content/uploads/2016/10/myAwesomemap.zif, the shortcode will look like this
[zoomify file="http://example.com/wp-content/uploads/2016/10/myAwesomemap.zif", skin="Default"].

I am not connected to Zoomify in any way, I coded this plugin for personal use and figured this may come in handy for other Zoomify users.

For now the plugin only supports one Zoomify image per page or post, but support for more images will be added in the future.

### Installation

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Upload your .zif files via the WordPress media section
4. Use the shortcode [zoomify file={fileUrl} skin="Default"] shortcode to create the Zoomify box on any post or page.


### Frequently Asked Questions

Can I have more then one Zoomify image on a page or post?

At the moment this plugin only supports one Zoomify image per page or post.

Can I add more skins to the plugin?

You can by uploading your custom skins to [your site url]/wp-content/plugins/gh-zoomify/assets/Skins] and use the foldername in the
shortcode. Please use the Zoomify style to name the folder. First letter uppercase and no spaces. For example 'Mycustomskin'.

Can I apply extra styling to the Zoomify container block?

The styling of the containerblock is kept as clean as possible, so you can style away by selecting #zoomifyContainer in your own CSS file
or your theme's custom CSS section.

### Changelog

= 1.0 =
* First stable release

== Upgrade Notice ==

= 1.0 =
* First stable release
