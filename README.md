# hexo-theme-changjinglu
Based on [hexo-theme-dxx](https://github.com/fuzhouxxdong/hexo-theme-dxx)
which is base(d) on [hugo-theme-cactus-plus](https://github.com/nodejh/hugo-theme-cactus-plus)
which is based on [hugo-cactus-theme](https://github.com/digitalcraftsman/hugo-cactus-theme)
which is based on the default theme for [Cactus](https://github.com/eudicots/Cactus) & [kactus](https://github.com/nickbalestra/kactus)

:smiling_imp:

## Caveat empdor
This theme currently has no consideration for 'shareability'. Ie, I've got images and stuff linked in here that are probably not relevant ***for you***.
Also, before this I'd never used jade/pug templates or Hexo. This code is probably awful.

## Live Preview
Assuming I haven't broken it, you can [check this theme out here](https://jarrod.linahan.id.au/).

## Installation
Install the theme's plugin dependencies:

- hexo-renderer-pug
- hexo-wordcount

Clone the theme from GitHub
```shell
git clone https://github.com/nahanil/hexo-theme-changjinglu.git themes/changjinglu
```
Aaaand, if you need to update it at any point
```shell
cd themes/changjinglu
git pull origin master
```

## Configuration

```yaml
theme_config:
  language: en
  # Date format used at the top of blog posts
  date_format: "MMM DD, YYYY h:mm"

  ## author is used in footer copyright line
  author: Jarrod Linahan
  # I don't think these two actually do anything...
  description: good good study day day up

  # Set the links shown in the top menu
  menu:
    Home: /
    Words: /blog
    Things: /portfolio
    About: /about

  # Add Google site verification/Google Analytics
  google_site_verification:
  google_analytics:

  # Add Matomo analyitcs
  # See: https://matomo.org/
  matomo:
    url: https://matomo.example.com/
    site_id: 2
    track_no_js: true

  disqus:
    enable: false
    shortname:

  # Use Isso for comments
  # See: https://posativ.org/isso/
  isso:
    enable: true
    host: https://isso.example.com/
```

## TODO
* Revisit how those images are loaded into the header so it can be more flexible for other users
* 翻譯 - 有人要幫我嗎？
* .. other stuff :see_no_evil:

## For my information
http://www.codeblocq.com/assets/projects/hexo-theme-clean-blog/tags/
^^ This is kinda where I got how to add the tag/category pages

## License
MIT
