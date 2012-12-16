OCT2 - a modified version of octopress classic theme (distributed under the same license as Octopress, [The MIT license](https://github.com/imathis/octopress#license) ).

I've included modifications made by Alessandro Melandri. For details, see ["Octopress Theme Customization"](http://melandri.net/2012/02/14/octopress-theme-customization/). Also included are [css formatting for tables](http://programus.github.com/blog/2012/03/07/add-table-data-css-for-octopress/) and 4 icons from free-hand drawn [Sketch icons](http://www.charfishdesign.com/19-free-hand-drawn-sketch-icons/).

If you want to enable MathJax,

```
$ cd .themes/oct2/source/_includes/custom/
$ cp head.mathjax.html head.html
```

*Installing*

```
$ git clone https://github.com/bijumon/oct2.git .themes/
$ rake install["oct2"] 
```

You also need to add nav.html to default asides in *_config.yml*

```
default_asides: [asides/nav.html, asides/recent_posts.html ....
```

![Oct2 screenshot](https://raw.github.com/bijumon/oct2/master/oct2.png)
