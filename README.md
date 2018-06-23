# Yanagi Ghost Theme 1.0.0

This is my fork of [Willow Ghost Theme 4.1](https://github.com/raivis-vitols/ghost-theme-willow) by Raivis Vitols.

## Theme Compatibility
Theme is fully compatible with Ghost 1.X versions. I'm in the process of adding multilanguage support.

## Theme Demo

This theme is currently being used on my personal blog - [https://www.alexandremercier.jp/](https://www.alexandremercier.jp/).

## Compiling SASS & Minifying JavaScript

The theme is using the original Gruntfile.js. I'll try to update it and make a Webpack, just to be like the cool kids.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">That one developer still using a Gruntfile <a href="https://t.co/OHOc4UTaxV">pic.twitter.com/OHOc4UTaxV</a></p>&mdash; I Am Devloper (@iamdevloper) <a href="https://twitter.com/iamdevloper/status/991687844770058240?ref_src=twsrc%5Etfw">May 2, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


Anyway, requires Grunt task runner & NPM to be installed.
```shell
$ npm install -g grunt-cli
$ cd content/themes/[theme-folder]
$ npm install
$ grunt
```
## Editing Social Links and Promo Links

Edit the `content/themes/[theme-folder]/partials/sidebar.hbs` file. Social links are in DIV with class `c-sidebar-contact-links` and  promo links are in `c-sidebar-promotion-links` DIV - just edit the anchors added inside them.

## Enabling Disqus Comments Box

1. Edit the `content/themes/[theme-folder]/post.hbs` file, uncomment `<!--{{> "comments"}}-->` partial inclusion.

2. Replace Disqus embed code with your site code. Edit `content/themes/[theme-folder]/partials/comments.hbs` file and replace `loadDisqusComments` function body with Disqus embed code function.

## Screenshots

I don't have time for this.
