---
layout: default # adjusts the format of the site page according to what's available in the `_layout/` directory
title: Test Page # This is what will appear if included in header
---



Let's see if this thing is working.

[//]: # "There are multiple ways to insert comments. This is one."


[//]: # "{# This type of comment doesn't work #}"


{% comment %}
This is another way to comment. Need to use this if trying to comment something that has tags in it otherwise the code will try to be interpreted.
{% endcomment %}

{% comment %}
To bring in material from a separate document, use `{% include_relative PATH/FILENAME %}`. Can alternatively use {% include FILENAME %} that will incorporate a file so long as it's in `_include/` dir. Should work for `.md` and `.html`. If using, need to remove yaml header from file
{% endcomment %}

{% include_relative about.md %}

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:

[//]: # "To include a hyperlink, put [DISPLAY_TEXT][HYPERLINK_TAG] where DISPLAY_TEXT is the text shown on the webpage as the hyperlink and HYPERLINK_TAG can be found at the bottom of the page in the format [HYPERLINK_TAG][URL]. The benefit of using this form of hyperlinking is the same hyperlink can be used in more than one place and it's easy to change when necessary."

[jekyll][jekyll-organization] / 

[//]: # "This is an alternative way to reference a hyperlink by using [DISPLAY_TEXT][URL] where DISPLAY_TEXT is the text shown on the website that serves as the hyperlink."

[minima](https://github.com/jekyll/minima) 


[//]: # "This is an example of creating a hyperlink tag that you can use in multiple places throughout a given document in the form of [HYPERLINK_TAG][URL]"

[jekyll-organization]: https://github.com/jekyll