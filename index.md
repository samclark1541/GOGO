---
title: Home
---

<div>
    <img src="{{ '/images/octocat.jpg' | absolute_url }}" alt="github octocat" style="width:45%;" >
    <img src="{{ '/images/jekyll.png' | absolute_url }}" alt="jekyll icon" style="width:45%;" >
</div>

# Build a Website with Jekyll and GitHub Pages

With [GitHub pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/) you can quickly create and publish a website for free!
It is an ideal solution for creating a simple project or personal site to highlight your academic work.

This workshop will introduce the basics of using free hosting from GitHub Pages which is integrated with the popular static website generator Jekyll.
You will learn how to set up a project repository, write content in Markdown, and publish your site, all using GitHub's user friendly web interface.
Advanced usage of Jekyll for local web development is introduced final section.

This workshop partners well with [Get Git](https://evanwill.github.io/get-git/){:target="_blank"}, which is offered earlier in the semester.
Experience with HTML will be helpful, but not necessary.

Watch [workshop screen cast](https://youtu.be/SWVjQsvQocA){:target="_blank"} (2017) for full content.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
