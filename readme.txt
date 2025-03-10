=== WP e-Commerce - Custom Fields ===

Contributors: visser, visser.labs
Donate link: https://www.visser.com.au/donations/
Tags: e-commerce, wp-e-commerce, mod, custom fields, store templating
Requires at least: 2.9.2
Tested up to: 5.0
Stable tag: 1.6
License: GPLv2 or later

== Description ==

Add and manage custom Product meta details within WP e-Commerce.

For more information visit: http://www.visser.com.au/wp-ecommerce/

== Installation ==

1. Upload the folder 'wp-e-commerce-custom-fields' to the '/wp-content/plugins/' directory

2. Activate 'Custom Fields for WP e-Commerce' through the 'Plugins' menu in WordPress

== Usage ==

==== In WP e-Commerce 3.7 ====

1. Open Store > Attributes within the WordPress Administration

==== In WP e-Commerce 3.8 ====

1. Open Products > Attributes within the WordPress Administration

====

2. Create new custom Product meta fields by clicking Add New

==== In WP e-Commerce 3.7 ====

3. Open Store > Products and select a Product

==== In WP e-Commerce 3.8 ====

3. Open Products and select a Product

====

4. Fill in your custom Product meta value and copy the provided PHP snippet into your template

Done!

== Support ==

If you have any problems, questions or suggestions please join the members discussion on my WP e-Commerce dedicated forum.

http://www.visser.com.au/wp-ecommerce/forums/

== Changelog ==

= 1.6 =
* Fixed: TinyMCE now showing for Textarea (with Editor) (thanks Alex)

= 1.5.9 =
* Fixed: Detection of WP e-Commerce version failing
* Changed: Compatibility with WordPress 4.8.2

= 1.5.8 =
* Changed: Compatibility of Attributes with Product Importer Deluxe

= 1.5.7 =
* Fixed: Compatibility with WP e-Commerce 3.11+

= 1.5.6 =
* Fixed: Compatibility with WP e-Commerce 3.9

= 1.5.5 =
* Fixed: Attribute menu not visible under Products
* Changed: Removed $wpsc_cf global
* Added: WPSC_CF prefixed Plugin constants

= 1.5.4 =
* Fixed: Product Importer Deluxe CRON support
* Fixed: WP_DEBUG errors
* Changed: Hide Add New button from header

= 1.5.3 =
* Fixed: Duplicate function error

= 1.5.2 =
* Added: Added wpsc_cf_get_value()

= 1.5 =
* Added: Custom template support for Layouts

= 1.4.9 =
* Added: Attribute menu option to Add New top admin bar

= 1.4.8 =
* Fixed: Error on settings screen

= 1.4.7 =
* Added: Settings screen
* Changed: Moved Settings to Settings screen
* Fixed: Assigning multiple checkbox values to Products

= 1.4.6 =
* Fixed: Validation for Product Importer Deluxe integration
* Added: Manage Attribute link to Add/Edit Products

= 1.4.5 =
* Fixed: Product Importer Deluxe integration error
* Changed: Updated readme.txt for Attributes

= 1.4.4 =
* Changed: Moved Product Importer Deluxe integration into Plugin
* Added: Checkbox and Radio Types
* Changed: Re-labeled references from Custom Fields to Attribute

= 1.4.3 =
* Fixed: Custom Fields not saving more than one field

= 1.4.1 =
* Changed: Using checked() and selected()
* Fixed: Show name is turned on by default for new custom fields
* Changed: Using the 'slug' attribute only displays the custom field value
* Changed: Using wp_parse_args() for slug attribte processing

= 1.4 =
* Added: Show name option to custom field
* Added: Prefix and suffix options to custom field

= 1.3.9 =
* Fixed: WP e-Commerce Plugins widget markup

= 1.3.8 =
* Fixed: Styling issue within Plugins Dashboard widget

= 1.3.7 =
* Added: Alt. switch to wpsc_get_action()

= 1.3.6 =
* Fixed: Issue introduced with wpsc_get_action()

= 1.3.5 =
* Added: wpsc_get_action() to common.php
* Changed: Updated how Positions are displayed within Settings
* Fixed: Update not triggering on Plugin update

= 1.3.4 =
* Fixed: First time activation not firing
* Fixed: Performance improvements for WP e-Commerce Plugins widget
* Added: Automatic Plugin updates

= 1.3.3 =
* Added: Integrated Version Monitor into Plugin

= 1.3.2 =
* Added: Auto-generate slugs for custom fields
* Changed: Reformatted readme.txt
* Added: Order option added to custom fields

= 1.3.1 =
* Added: WYSIWYG editor option as field type

= 1.3 =
* Added: 'slug' attribute to output individual custom fields within wpsc_the_custom_fields()

= 1.2.9 =
* Added: ID support to individual custom fields

= 1.2.8 =
* Added: Default empty value to Add/Edit Products for dropdown

= 1.2.7 =
* Changed: Dropped support of wpsc_is_single_product()
* Fixed: Non-save state for dropdown type

= 1.2.6 =
* Changed: Replaced wpsc_is_single_product()
* Changed: Cleaned up template files
* Changed: Removed wpsc_cf_check_plugin_version()

= 1.2.5 =
* Added: Support for drop-down custom fields

= 1.2.4 =
* Added: Separate template files
* Added: Layouts; table, ordered and unordered list
* Added: Template tags

= 1.2.3 =
* Fixed: Hide Custom Fields header if no Custom Fields are entered for a Product
* Added: Header option
* Added: Show/hide Header option
* Fixed: Updated readme.txt

= 1.2.2 =
* Added: Position and manual placement template tag
* Changed: Replaced existing template tag hint with description

= 1.2.1 =
* Changed: Migrated Plugin prefix from 'vl_wpsccf' to 'wpsc_cf'

= 1.2 =
* Changed: Moved ..._check_plugin_version() to functions.php

= 1.1 =
* Added: Support for custom field types (field/textarea)

= 1.0.5 =
* Fixed: Missing wpsc_get_major_version()

= 1.0.4 =
* Fixed: Bug affecting Plugin update notification

= 1.0.3 =
* Added: Urgent support for WP e-Commerce 3.8+

= 1.0.2 =
* Fixed: Better support for WP e-Commerce 3.8 Official (thanks Ryan Waggoner)

= 1.0.1 =
* Added: Support for WP e-Commerce 3.8
* Fixed: Missing Settings menu for WP e-Commerce 3.8

= 1.0 =
* Added: First working release of the Plugin

== Disclaimer ==

It is not responsible for any harm or wrong doing this Plugin may cause. Users are fully responsible for their own use. This Plugin is to be used WITHOUT warranty.
