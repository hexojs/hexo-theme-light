# Light

A simple theme for [Hexo].

## Install

Execute the following command and modify `theme` in `_config.yml` to `light`.

```
git clone --depth 1 https://github.com/hexojs/hexo-theme-light themes/light
```

``` diff
_config.yml
- theme: some-theme
+ theme: light
```

## Update

Execute the following command to update Light.

```
cd themes/light
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

widgets:
- search
- category
- tag
- twitter

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

fancybox: true

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

## Features

### Gallery Post

![Gallery Post](https://raw.githubusercontent.com/hexojs/hexo-theme-light/site/source/screenshots/gallery-post.gif)

```
---
layout: photo
title: Gallery Post
photos:
- https://i.postimg.cc/c49xRqRP/1.jpg
- https://i.postimg.cc/288jLjZ4/2.jpg
- https://i.postimg.cc/T2cYP5pd/3.jpg
---
```

### Link Post

![Link Post](https://raw.githubusercontent.com/hexojs/hexo-theme-light/site/source/screenshots/link-post.gif)

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

### Tweet Widget

![Tweet Widget](https://raw.githubusercontent.com/hexojs/hexo-theme-light/site/source/screenshots/tweet-widget.gif)

### Fancybox

![Fancybox](https://raw.githubusercontent.com/hexojs/hexo-theme-light/site/source/screenshots/fancybox.gif)

[Hexo]: http://zespia.tw/hexo/
[Fancybox]: http://fancyapps.com/fancybox/
