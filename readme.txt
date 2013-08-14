=== Apply with Gravity Forms for WP Job Manager ===

Author URI: http://astoundify.com
Plugin URI: http://astoundify.com
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=contact@appthemer.com&item_name=Donation+for+Astoundify WP Job Manager Gravity Forms
Contributors: spencerfinnell
Tags: job, job listing, job apply, gravity forms, wp job manager
Requires at least: 3.5
Tested up to: 3.5
Stable Tag: 1.2
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Allow themes using the WP Job Manager plugin to apply via a defined Gravity Form.

== Description ==

Allow themes using the WP Job Manager plugin to apply via a defined Gravity Form.

= Where can I use this? =

Astoundify has released the first fully integrated WP Job Manager theme. Check out ["Jobify"](http://themeforest.net/item/jobify-job-board-wordpress-theme/5247604?ref=Astoundify)

== Frequently Asked Questions ==

= Nothing happens when I set the Gravity Form ID? =

It is up to the theme to respect your choice to use this plugin (as there is no way to automatically insert the form). The theme you are using must add:

`if ( class_exists( 'Astoundify_Job_Manager_Apply' ) ) :
	echo do_shortcode( '[gravityform id="' . get_option( 'job_manager_gravity_form' ) . '" title="false" ajax="true"]' );`

== Installation ==

1. Install and Activate
2. Go to "Job Listings > Settings" and enter the ID of the form you would like to use.

== Changelog ==

= 1.0: August 14, 2013 =

* First official release!