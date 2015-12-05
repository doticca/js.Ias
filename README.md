js.Ias
======

The js.Ias module contains the jQuery Infinite Ajax Scrolling plugin and related script libraries for Orchard CMS

After you enable the module your Blog posts no longer use the Core Pager Orchard functionality but automatically get into infinity scrolling mode. Every time the user scrolls towards the end of the feed, it loads the next page of posts and inserts them into the DOM without reloading your content. On the User eXperience level this looks and feels exactly like infinite scrolling.

NOTE: Once you have enabled the module take a look at your Blog admin page ! welcome to orchard dashboard infinite scrolling :)

For this module to work you have to remove any Pager*.cshtml files from your themes view folder.
TheThemeMachine for example has three files:
Pager.chtml
Pager.First.cshtml
Pager.Last.cshtml
* you have to remove all three of them to make this module work *

Ias now works for Blog posts out of the box, just enable the supplementary module Orchard.jQuery.Ias.Blogs and you have infinite scrolling in both admin and front end mode.

*** new features ***
project hosted in codeplex using mercurial
fixed javascript functions to not hit in admin mode
added the orchard.jquery.ias.blogs module to enable ias for blog posts out of the box
