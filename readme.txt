=== AlternativeTo Widget ===
Contributors: stuckish 
Tags: software,alternative software,widget,alternativeto
Requires at least: 2.5
Tested up to: 2.9.1
Stable tag: 0.71
Author URI: http://alternativeto.net
Plugin URI: http://blog.alternativeto.net

Plugin to show information about an application and it's top alternatives on AlternativeTo.net.

== Description ==

AlternativeTo is a website dedicated to give you alternatives to software. This plugin let you display information about the application you write about on your blog and also a list of it's top rated alternatives.

The plugin is using [our API](http://blog.alternativeto.net/post/255659956/a-first-look-at-the-alternativeto-api "AlternativeTo API") and we really encourage you to try it out. And if you have more experience in PHP/Wordpress development than us feel free to build your own plugins based on the API or send us suggestions how to make this plugin better. We would be happy to add you as a contributor to the plugin.

== Installation ==

Note! Requires <?php wp_head(); ?> in the header.php file.

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

Then add [alt2app app=application-name category=desktop] to add the widget where you added the shortcode.

The "application-name" is the name of the application the exact same way as the url to the app on AlternativeTo. For example Adobe Photoshop has the url.

http://alternativeto.net/desktop/adobe-photoshop/

Then the application name is "adobe-photoshop".

== Screenshots ==

1. Default theme
2. Small theme
3. Minimal theme
