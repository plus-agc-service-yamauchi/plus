=== Lovecraft ===
Contributors: Anlino
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=anders%40andersnoren%2ese&lc=US&item_name=Free%20WordPress%20Themes%20from%20Anders%20Noren&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
Requires at least: 4.4
Tested up to: 5.0
Stable tag: trunk
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html


== Installation ==

1. Upload the theme
2. Activate the theme

All theme specific options are handled through the WordPress Customizer.


== Licenses ==

Lato
License: SIL Open Font License, 1.1 
Source: https://fonts.google.com/specimen/Lato

Playfair Display
License: SIL Open Font License, 1.1 
Source: https://fonts.google.com/specimen/Playfair+Display

Genericon font icon set
License: GNU GPL 2.0
Source: http://genericons.com

Included header image
License: CC0 Public Domain 
Source: http://www.unsplash.com

screenshot.png images
License: CC0 Public Domain 
Source: http://www.unsplash.com

Doubletaptogo.js
License: MIT License
Source: https://github.com/dachcom-digital/jquery-doubletaptogo


== Changelog ==

Version 1.28 (2018-12-20)
-------------------------
- Combined index.php, archive.php, and search.php into index.php
- Combined content.php and content-aside.php into content.php
- Combined single.php and page.php into singular.php
- Updated the full width page template to use the same code as singular.php
- Fixed incorrect call of Lovecraft_Recent_Posts in fallback sidebar widgets
- Moved the post meta output into a function, to reduce duplicate code
- Removed output of unneccessary title attributes
- Added focus outline to link elements
- Changed the toggles to button elements
- Added screen reader text to the toggles

Version 1.27 (2018-12-07)
-------------------------
- Fixed Gutenberg style changes required due to changes in the block editor CSS and classes
- Fixed the Classic Block TinyMCE buttons being set to the wrong font

Version 1.26 (2018-11-30)
-------------------------
- Fixed Gutenberg editor styles font being overwritten

Version 1.25 (2018-10-20)
-------------------------
- Updated with Gutenberg support
	- Gutenberg editor styles
	- Styling of Gutenberg blocks
	- Custom Lovecraft Gutenberg palette
	- Custom Lovecraft Gutenberg typography styles
- Added option to disable Google Fonts with a translateable string
- Updated theme description
- Removed the languages sub folder, since that is handled by WordPress.org

Version 1.24 (2018-05-24)
-------------------------
- Fixed output of cookie checkbox in comments
- Added missing paranthesis in image.php

Version 1.23 (2018-04-21)
-------------------------
- Fixed error in comments.php

Version 1.22 (2018-04-21)
-------------------------
- Added a Customizer setting for displaying the sidebar on tablet and mobile
- Fixed errors pointed out by Theme Sniffer
- Cleaned up the CSS a bit
- Code review with the Theme Sniffer WordPress-Extra ruleset

Version 1.21 (2018-01-21)
-------------------------
- Fixed layout issue with the website field label in the comment form in some browsers
- Added alt text to header image, extra escapes of values at output

Version 1.20 (2017-12-05)
-------------------------
- Fixed recent posts widget showing currently viewed post regardless of date

Version 1.19 (2017-12-03)
-------------------------
- Fixed bug caused by leftover code after update in recent posts widget
- Went back to full-length ternarys to prevent issue with older versions of PHP

Version 1.18 (2017-12-02)
-------------------------
- Updated to the new readme.txt format, with changelog.txt incorporated into it
- Added a demo link to the stylesheet theme description
- Added a deliberate dependency order to the stylesheet enqueueing
- Same for scripts enqueues
- Made all functions in functions.php pluggable
- Replaced a new WP_Query in widgets/recent-posts.php with a get_posts()
- Fixed genericons path
- Fixed notice in comments.php
- Changed closing element comment structure
- General code cleanup, improvements in readability
- Fixed potential overflow issue on mobile for the blog title and logo

Version 1.17 (2016-06-18)
-------------------------
- Added the new theme directory tags
- Added screen reader text

Version 1.16 (2015-08-11)
------------------------- 
- Added clearing divs after the post content on archive pages and single posts/pages
- Widgets now use the __construct() function in prep for WP 4.3
- Singular post titles now use the h1 element for SEO reasons
- Set the standard number of images in the Flickr widget to six
- Set the infinite handle button to antialiased

Version 1.15 (2014-04-07)
------------------------- 
- Replaced wp_print_styles() with wp_enqueue_styles() in functions.php

Version 1.14 (2014-03-23)
------------------------- 
- Renamed xx_XX.pot to lovecraft.pot
- Replaced doubletaptogo.min.js with doubletaptogo.js (non-minified)
- Removed the wp_is_mobile() function from functions.php
- Replaced get_stylesheet_directory_uri() with get_template_directory_uri() so that child themes load Genericons correctly

Version 1.13 (2014-03-09)
------------------------- 
- Added fallback widgets that are displayed in the sidebar if no widgets have been selected
– Added missing namespaces in widgets
– Updated the Swedish translation

Version 1.12 (2014-03-09)
------------------------- 
- Added validation for instances in widgets

Version 1.11 (2014-02-09)
------------------------- 
- Removed a duplicate title function causing the page title to be added twice to <title></title>

Version 1.10 (2014-01-29)
------------------------- 
- Added additional missing esc_attr() to widgets/flickr-widget.php

Version 1.09 (2014-01-29)
------------------------- 
- Added missing esc_attr() to widgets and header.php
- Replaced the query in widgets/recent-posts.php with a custom wp_query
- Wrapped the custom Read More text link in a paragraph element
- Optimized the comments respond form for subscribe checkboxes

Version 1.08 (2014-01-01)
------------------------- 
- Dialed up the contrast in the design
- Changed the layout of comments
- Made minor changes to the Swedish translation

Version 1.07 (2014-01-01)
------------------------- 
- Added support for the aside post format (sorry, theme reviewer)

Version 1.06 (2014-01-01)
------------------------- 
- Improved the styling of comments
- Added a missing element to the custom accent color function
- Broke promise on making the last update the last update before release

Version 1.05 (2014-01-01)
------------------------- 
- Improved the styling of the footer (last update before release, promise)

Version 1.04 (2014-01-01)
------------------------- 
- Fixed a bug in the title tag backwards compatibility code

Version 1.03 (2014-01-01)
------------------------- 
- Added support for the new title tag theme feature

Version 1.02 (2014-01-01)
------------------------- 
- Removed a misplaced comma in the theme meta information tags
- Removed a add_shortcode function

Version 1.01 (2014-01-01)
------------------------- 
- Added a sanitize_hex_color callback to the custom accent color control

Version 1.00 (2014-01-01)
------------------------- 