=== Anonymize Links ===
Contributors: Schalk Burger
Donate link: http://schalkburger.za.net
Tags: anonymize, anonymise, mask, hide referrer, blank referrer, referral, logs, visitors, privacy
Requires at least: 2.0.2
Tested up to: 4.3
Stable tag: 1.1

Anonymize all your external links with the href.li service.

== Description ==

You can use this plugin to prevent your site from appearing in the server logs of referred pages as a referrer. The operators of the referred pages cannot see where their visitors come from any more. 

For example, this plugin will automatically convert all external links to this format 

https://href.li/?http://example.com/

This is an anonymous link to example.com which prevents the original site from appearing as a referrer in the log files of the referred page.

Plugin based on the WP Blank Referer by blackhatzen.

== Installation ==


1. Upload **anonymize-links** to the **/wp-content/plugins/** directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. (Optional) Add domains that you don't want to anonymize under Settings > Anonymize Links

== Frequently Asked Questions ==

= What is the advantages of anonymizing your external links? =

Webmasters can use this tool to prevent their site from appearing in the server logs of referred pages as referrer. The operators of the referred pages cannot see where their visitors come from any more.

Some people do it privacy. Some people do it to keep their sources unknown.

= What is a referer? =

[Click here](http://en.wikipedia.org/wiki/Referer) for Wikipedia's description.

== Changelog ==

= 1.1 =
* Updated the plugin to use the href.li service

= 1.0 =
* Initial release