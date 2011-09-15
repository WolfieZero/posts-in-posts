=== Posts in Posts ===
Contributors: wolfiezero
Tags: posts, recent, category, tag
Requires at least: 3.1
Tested up to: 3.1
Stable tag: 0.5

Posts in Posts grabs posts based on tag, category or just recent, and display them inline with a post

== Description ==

Posts in Posts will allow you to grab recent posts based on category, tag or just recent posts. Then it will display thoses posts in a list in the post or page you have called the PinP on. It's as easy as all you need to do is write a HTML-esq bit of code.

[showposts type="category" name="Lipsum" limit="4" date="d-m-Y"]

This will then output 4 posts from the category 'Lipsum'.

All posts are outputted using an un-ordered list.

Options are:

* 'type'
**'category'
**'tag'
**'recent'
**blank - will use 'recent'

*'name'
**the name of a given category or tag in your wordpress taxonmy
**if left blank then it will resort to outputting nothing unless the type is 'recent' or blank

*'limit'
**the number of posts you want to display in a given call
**if left blank then it resolves to the default of '5'

*'date'
**use the standard date format for php - http://php.net/manual/en/function.date.php
**if left blank then it won't display a date

== Changelog ==

= 0.5 =

* First available public release.
