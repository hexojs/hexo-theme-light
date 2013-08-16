# Hexo: Twitter Bootstrap Theme

> ### What is Twitter Bootstap
>
> Sleek, intuitive, and powerful front-end framework for faster and easier web development.
>
> See: [Twitter Bootstap](http://getbootstrap.com/2.3.2/examples/fluid.html)
>
>
> ### What is Hexo
>
> A fast, simple & powerful blog framework, powered by Node.js.
>
> See: [Hexo][Hexo]

## Note

I would consider this beta. I've tested most elements my liking, but only on Chrome for Linux. It needs further testing before I'll call it done.

## Install

Execute the following command and modify `theme` in `_config.yml` to `twbootstrap`.

```
git clone git://github.com/tommy351/hexo-theme-twbootstrap.git themes/twbootstrap
```

## Update

Execute the following command to update:

```
cd themes/twbootstrap
git pull
```

## Config

Default config:

``` yaml
# Site default meta keywords
#keywords: site, wide, default, keywords

# path to bootstrap css template if not specified,
# uses full bootstrap-combined.min.css
#
# These free themes are provided by my firends at http://bootstrapcdn.com
#
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/amelia/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/cerulean/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/cosmo/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/cyborg/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/flatly/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/journal/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/readable/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/simplex/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/slate/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/spacelab/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/spruce/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/superhero/bootstrap.min.css
#bootstrap_css: //netdna.bootstrapcdn.com/bootswatch/2.3.2/united/bootstrap.min.css

# inverse bootstrap navbar
#bs_nav_inverse: true

# This section turns on javascript components,
# they're off by default to make things faster.
#bootstrap_js: true
#imagesloaded_js: true # gives images a loading icon
#fancybox: true

# stick footer to page bottom
sticky_footer: true

# don't use this without sticky_footer
#footer_color: 'black'

# Include gravatar to left of page title in navbar.
# It will overflow navbar a bit intentionally.
#
# NOTE: this should be considered experimental
gravatar:
  # e.g.
  #gravatar: ed808193b8c2c8516715816f90a005b2 # that's me

menu:
  Home: /
  Archives: /archives

widgets:
- search
- category
- tag

excerpt_link: read more

twitter_id:
facebook_id:
linkedin_id:
github_id:

addthis:
  enable: true
  pubid:
  twitter: true
  facebook: true

google_analytics:
rss:

disqus_shortname:

```

## Features

### Link Post

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

### Fancybox

See: [Fancybox][Fancybox]

[Hexo]: http://zespia.tw/hexo/
[Fancybox]: http://fancyapps.com/fancybox/
