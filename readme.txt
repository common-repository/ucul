=== Plugin Name ===
Contributors: mrlemonade
Donate link: http://goo.gl/aMmyG
Tags: affiliate, links, seo, javascripts, google, post
Requires at least: 3.0.4
Tested up to: 3.0.4
Stable tag: 0.1

Ucul on the fly contextual text replacement plugin could help your seo needs.

== Description ==

Ucul on the fly contextual text replacement plugin could help your seo needs. It can replace a set of keywords into new keywords, html tags or event a javascript. Basically it's like simple text rewriter but generated on the fly using javascript rather than parsed manually by php.

Features

* auto search and parse all html id/class name to look for keywords.
* manually set html id/class name.

Example of a good usage:

*   rewrite such regular text keywords into anchored text link
*   replace text emoticons with an img tag
*   or anything you want to replace
<br />
plugin by <a href="http://moshimon.wordpress.com/">mrlemonade</a>

== Installation ==

How to Install

1. Extract `ucul.zip` and it will provide `ucul` directory with files in it
1. upload  `ucul` to the `/wp-content/plugins/` directory so you will have `/wp-content/plugins/ucul/`
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Configure Ucul in, Settings -> Ucul, to suit your needs.

== Frequently Asked Questions ==

= Example use of this plugin? =

* example, you have content like this in your wp post:

"Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus."

* and those post contest is inside `<div class="mypost"></div>`

so, you will set Ucul, like this:

Custom html class: <strong>mypost</strong><br />
Custom html id: *leave empty*
<br /><br />
keywords and replacements:

<strong>Aenean</strong>|<strong>Aenean is Cool</strong><br />
<strong>Nam quam nunc</strong>|<strong>`<a href="http://whateverlink.com">blah</a>`</strong><br />

so it will replace all found string
'Aenean' string into 'Anean is Cool'<br />
'Nam quam nunc' into 'Nam quam nunc|`<a href="http://whateverlink.com">blah</a>`'<br />

So basically find1|replace1 in pair with newlines for another pair.

== Screenshots ==

1. ucul.jpg
2. ucul-in-action.jpg

== Changelog ==

= 0.1 =
* Initial public release.