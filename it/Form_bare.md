---
# Front matter of "bare" page

# Theme to use. Resides in the "_layouts" folder.
layout: default

# Page title. If omitted, the page will not be included in the navbar.
title: Form

#################################################################

# Specifies the order of the current page from the point of view of the navbar. Can have repetition in the numbers, for parent-child hierarchies.
nav_order: 3

# Let exclude the page from the navbar
nav_exclude: false

# Let exclude the page from the built-in search engine
search_exclude: false

#################################################################

# Set "true" if this page has childrens, "false" otherwise.
has_children: false

# If this page is some page's child, specify the parent's name, otherwise comment out the option. If this page is some page's grandchild, specify grandparent's name, otherwise comment out the option.
parent: BitEvent
# # grand_parent: Index

# If this page is a parent page, a Table Of Contents will be automatically generated containing all related child pages. Use the option below to disable this functionality. Should always be set to "false".
has_toc: false

#################################################################

# Specify the language of the page target of the redirection. So, copy the "lang"-option value of that page. "availableLanguages" is not expected here. The language should be matched in the "redirect_to" URL.
lang: it

#################################################################

# Bare: redirect page
redirect_to:
    - /it/#form
---

<!-- Bare Page -->

<i class="fa-solid fa-gear fa-spin fa-2x"></i>&nbsp;&nbsp;Loading. Please standby.

Still on this page? Try <a href="javascript:reloadPage();">reloading</a> it or opening a new tab.