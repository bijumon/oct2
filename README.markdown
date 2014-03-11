**Preview** at [http://bijumon.github.io/oct2](http://bijumon.github.io/oct2)

OCT2 - a modified version of octopress classic theme (distributed under the same license as Octopress, [The MIT license](https://github.com/imathis/octopress#license) ).

I've included modifications made by Alessandro Melandri. For details, see ["Octopress Theme Customization"](http://melandri.net/2012/02/14/octopress-theme-customization/). Also included are [css formatting for tables](http://programus.github.com/blog/2012/03/07/add-table-data-css-for-octopress/) and [Font Awesome](http://fortawesome.github.io/Font-Awesome/) icons.

enabling MathJax requires using `kramdown` instead of `rdiscount`

```
markdown: kramdown
mathjax: true
```

*Installing*

```
$ git clone https://github.com/bijumon/oct2.git .themes/
$ rake install["oct2"]
```

*Changing the logo*

set 'logo' in _config.yml to an image in 'source/images' and style it using '#logo' in `sass/custom/_styles.scss`

```
# _config.yml
logo: portrait.png
```

![Oct2 screenshot](https://raw.github.com/bijumon/oct2/master/source/images/oct2.png)

[octopress](http://octopress.org/) was created by [Brandon Mathis](http://brandonmathis.com/) aka [@imathis](https://twitter.com/imathis).
[octopress logo](http://octopress.org/) was created by [david lanham](http://dlanham.com ) aka [@dlanham](https://twitter.com/dlanham).
