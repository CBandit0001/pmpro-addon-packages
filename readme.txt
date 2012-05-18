=== PMPro Addon Packages ===
Contributors: strangerstudios
Tags: pmpro, paid memberships pro, ecommerce
Requires at least: 3.0
Tested up to: 3.3.2
Stable tag: .1

Allow PMPro members to purchase access to specific pages. This plugin is meant to be a temporary solution until support for multiple membership levels is added to PMPro.

You must have the latest version of Paid Memberships Pro installed (currently 1.4.5).


== Description ==

Story
* Admin designates a post as an "addon package".
* Sets a price for access to the post. (pmproap_price)
* Selects which membership levels can purchase the package. (pmproap_levels)
* For users without access, the page will show a link to purchase at the bottom of the page.
* Purchase goes to either a new checkout page or the PMPro checkout page with some parameters passed in.
* After checking out, they are taken to a new confirmation page or the PMPro confirmation page with extra info.
* After purchasing, the user ID is added to post meta (pmproap_users). The post ID is also added to user meta (pmproap_posts).

Limitations
* Only one time charges.
* No tax.
* No discount codes.

== Installation ==

1. Upload the `pmpro-addon-packages` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Edit a post or page to set a price for it.

== Frequently Asked Questions ==

= I found a bug in the plugin. =

Please post it in the issues section of GitHub and we'll fix it as soon as we can. Thanks for helping. https://github.com/strangerstudios/pmpro-addon-packages/issues

= I need help installing, configuring, or customizing the plugin. =

Please visit our premium support site at http://www.paidmembershipspro.com for more documentation and our support forums.

Please Note: This plugin is meant as a temporary solution. Most updates and fixes will be reserved for when this functionality is built into Paid Memberships Pro. We may not fix the pmpro-addon-packages plugin itself unless it is critical.

== Changelog ==
= .1 =
* Initial release.