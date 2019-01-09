---
layout: post
title: How to install the Jekyll sitemaps plugin and improve your SEO
description: I was one of 30 attendees selected out of 2000+ applicants to attend a five-day immersion program for first-year computer science students focused on professional and technical development including coding, networking, personal branding, resume writing,interview skills.
modified: 2018-05-06
tags: [information, data]
comments: true
categories: [information]
pinned: true
---
{{ page.title }}
================

In the past several months I’ve made many incremental improvements to this website, including how I generate my Sitemap.xml. While my revisions are certainly not jaw dropping, they have definitely improved the quality of my sitemap and are thus worth writing about, if only to provide a reference point to other developers. To that end, here’s a note about the changes I’ve made in my current implementation.

# Sitemap.xml Generator for Jekyll

This a Jekyll plugin that generates a sitemap.xml file by traversing all of the available posts and pages and improving your Jekyll blog's SEO.

Sitemap.xml for Jekyll makes it easy for you to submit your site–and its content structure–to Google and other search engines. The sitemap file informs the search engines which URLs they should crawl thereby giving you a little more control over what they index and how they index it.

Using this Sitemaps plugin is straight-forward. Download the plugin, add it your project, and configure it so it properly creates the Sitemap.xml file. The site map will be generated automatically when you run jekyll to build your site.

How To Install Sitemap Generator Plugin on your Jekyll blog:

1. [Download](https://github.com/kinnetica/jekyll-plugins/blob/master/sitemap_generator.rb) the plugin onto your computer. Copy plugin file into your _plugins folder within your Jekyll project.
2. Ensure url is set in your config file (for example url: [http:tanaka.co.zw/](http://tanaka.co.zw/)
3. In your config file, change sitemap: filename: if you want your sitemap to be called something other than sitemap.xml.
4. Change the sitemap: exclude: list to exclude any pages that you don't want in the sitemap.
5. Change the sitemap: include_posts: list to include any pages that are looping through your posts (e.g. "/index.html", "/notebook/index.md", etc.). This will ensure that right after you make a new post, the last modified date will be updated to reflect the new post.
6. Run Jekyll: jekyll build to re-generate your site. A sitemap.xml should be included in your _site folder. You can check your _site folder to make sure the sitemap file is there.

Configuration defaults:

```javascript
sitemap:
    filename: "/sitemap.xml"
    exclude:
        - "/atom.xml"
        - "/feed.xml"
        - "/feed/index.xml"
    include_posts:
        - "/index.html"
    change_frequency_name: "change_frequency"
    priority_name: "priority"
```

Customizations:
If you want to include the optional ```changefreq``` and ```priority``` attributes, simply include custom variables in the YAML Front Matter of those files. The names of these custom variables are defined in the ```config``` file as ```sitemap: change_frequency_name:``` and ```sitemap: priority_name:```

This github repository offers really helpful directions on how to download and install the Jekyll Sitemaps plugin. 