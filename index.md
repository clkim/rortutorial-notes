---
layout: page
title: Notes for 'Ruby on Rails Tutorial by Michael Hartl'
description: Some notes taken while reading 'Ruby on Rails Tutorial by Michael Hartl' using Windows 7
subtitle: Windows 7
---
{% include JB/setup %}

### What are these pages?
I am reading the [new (beta) second edition](http://ruby.railstutorial.org/) online, and using Windows 7. These are informal notes I took for myself as I ran into road bumps due to being on Windows 7 and not a Mac. I am happy to **share them "as is,"** with the customary disclaimer that I can make NO REPRESENTATIONS OR WARRANTIES AS TO CORRECTNESS.

### Errata
I am also happy to receive corrections and suggestions on this topic by email to [clkim](mailto:clkim@ieee.org).

#### Help
However, if you have questions or encounter issues, please see the Tutorial's [Help](http://ruby.railstutorial.org/help) page on posting to [Stack Overflow](http://stackoverflow.com/) to engage the community. Unfortunately, I do not anticipate being able to respond to questions in any timely manner; thanks for understanding.

#### Convention
 `$>` denotes the Windows cmd prompt, usually in the application root directory, e.g. `C:\Sites\rails_projects\first_app>`

##### More Notes to come. Enjoy...
    
### Notes by Chapter in Tutorial:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
