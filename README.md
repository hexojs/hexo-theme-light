# Light

Default theme for [Hexo].

## Install

Execute the following command and modify `theme` in `_config.yml` to `light`.

```
git clone https://github.com/hexojs/hexo-theme-light.git themes/light
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

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

fancybox: true

google_analytics:
rss:

comment_provider: facebook
facebook:
  appid: 012345012345
  comment_count: 5
  comment_width: 840
  comment_colorscheme: light
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)
- **comment_provider** - "facebook" (to enable Facebook comments)
  - **appid** - Facebook AppId (from developer tools)
  - **comment_count** - Number of commends to show
  - **comment_width** - Width of comment box in pixels
  - **comment_colorscheme** - Color scheme
 
## Features

### Gallery Post


```
---
layout: photo
title: Gallery Post
photos:
- http://i.minus.com/ibobbTlfxZgITW.jpg
- http://i.minus.com/iedpg90Y0exFS.jpg
---
```

### Link Post

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

### Tweet Widget


### Fancybox


[Hexo]: http://hexo.io
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/
