---
layout:     post
title:      "Why Jekyll?"
excerpt:    "And Why Not Drupal?"
teaser:     "If you follow my open source contributions, it is no secret that I am and continue to be an avid Drupal user. So why did I choose to move my blog off of Drupal?"
author:     Chris Pliakas
date:       2013-12-03 20:00:00
categories: blog
tags:       [tech]
---

If you follow my open source contributions, it is no secret that I am and
continue to be an avid <span itemscope itemtype="http://schema.org/SoftwareApplication">
<a href="http://drupal.org" target="_blank" itemprop="sameAs">
<span itemprop="name">Drupal</span>
</a>
</span> user. So why did I choose to move my blog off of
Drupal, and more specifically why am I building it with
<span itemscope itemtype="http://schema.org/SoftwareApplication">
<a href="http://jekyllrb.com" target="_blank" itemprop="sameAs">
<span itemprop="name">Jekyll</span>
</a>
</span>
and hosting it on
<span itemscope itemtype="http://schema.org/Organization">
<a href="http://pages.github.com" target="_blank">
<span itemprop="name">GitHub</span> Pages
</a>
</span>?

The primary reason is that the revised architecture allows me to focus more on
writing by spending less time maintaining the blog platform. The secondary
reason is that I love to learn and enjoy challenging my own conclusions. One
of the most dangerous things you can do in my line of work is reject other
tools based on biased assumptions, because everything looks like a nail when
all you have is a hammer. Drupal can be configured as an excellent blogging
platform, however evaluating the right tool for the job must also account for
the people using it and the context in which it is being leveraged.

Jekyll is a command line tool that converts templates and text files into flat
HTML pages which is how it eliminates the maintenance headaches of any database
driven website. My design skills are equivalent to a kindergartner drawing a
blue duck with crayons, so it also helps to have a blank canvas where I can use
front end frameworks as they are documented without the overhead of integrating
them into a Drupal theme.

The time saved by a website building tool would be all for naught if the site
wasn't easy to host. GitHub Pages is a free, Jekyll-aware hosting solution
where deployments are automatically triggered when pushing commits to the
origin repository. If the model of GitHub Pages changes in the future, I can
always move my blog to another provider on a cheap plan since static websites
are portable and much less resource intensive than CMS based applications.

This architecture is admittedly not for everyone, but if you are command line
oriented and your site doesn't require complex page rendering logic, this setup
is a cost-effective solution that eliminates the complexity of database driven
systems. Given my affinity for GitHub workflows and the static nature of this
blog, it is a perfect fit for ChrisPliakas.com.
