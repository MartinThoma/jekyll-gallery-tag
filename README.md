jekyll-gallery-tag
==================

A Liquid tag for Jekyll sites that allows easy creation of 
wikpedia-style image galleries.

How To Install
===============
1. Copy `gallery_tag.rb` into `<your-jekyll-site>/_plugins`.
2. Add the styles from `style.css` to your stylesheets.

How To use
==========
Place a `gallery` tag in your content file, e.g.:
```
{% gallery columns="2" %}
    ../images/2013/10/bash-vs-zsh-cd.png    "Bash vs zsh: cd command completion"
    ../images/2013/10/bash-vs-zsh-git.png   "Bash vs zsh: Git prompt indicator"
    ../images/2013/10/bash-vs-zsh-spelling-correction.png   "Bash vs zsh: Spelling correction"
    ../images/2013/10/bash-vs-zsh-time.png  "Bash vs zsh: time command"
{% endgallery %}
```

Examples
========
* [post](https://github.com/MartinThoma/MartinThoma.github.io/blob/source/_posts/2013-10-22-working-terminal.md), [rendered post](http://martin-thoma.com/working-terminal/)

Changelog
=========
Version 1.0, 2014-01-06: Initial commit.

License
=======
This code is licensed under MIT License. 

What does this mean?

* You may use it if you like
* Don't blame me when thinks don't work (though you can file an issue)
* Please don't remove the link in the comments of `caption_tag.rb`.
  This might help others to find this plugin
