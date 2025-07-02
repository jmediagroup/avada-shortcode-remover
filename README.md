# avada-shortcode-remover
A simple plugin to clean Avada fusion shortcodes from your Wordpress posts.

=== Remove Avada Fusion Shortcodes ===
Contributors: J Media Group LLC
Tags: avada, fusion builder, shortcode cleanup, wordpress maintenance
Requires at least: 4.0
Tested up to: 6.5
Stable tag: 1.8
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==

Removes all [fusion_*] shortcodes from post content and converts any plain image URLs into proper <img> tags.

== Installation ==

1. Download the plugin ZIP file to your computer.
2. In your WordPress dashboard, navigate to Plugins > Add New > Upload Plugin.
3. Choose the downloaded ZIP file and click Install Now.
4. Activate the plugin.

== Usage ==

1. After activation, go to Tools > Remove Fusion Shortcodes in your WordPress admin menu.
2. Click the "Run Cleanup" button.
3. The plugin will:
    - Remove all [fusion_*] shortcodes from all published blog posts.
    - Convert any plain text image URLs (ending in .jpg, .jpeg, .png, .gif, .webp) into proper <img> tags.

== Notes ==

- This plugin only processes published blog posts (post_type=post).
- Always back up your site before running cleanup operations.
- You can deactivate and delete the plugin after cleanup is complete.

== Changelog ==

= 1.8 =
* Added readme.txt file

