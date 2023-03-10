My blog
=======

This repository holds code & contents of my [personal weblog](https://nicolas.perriault.net/).
It's a static website built using [Jekyll](https://jekyllrb.com) and the
[Hydeout theme](https://github.com/fongandrew/hydeout). It's hosted on
[Github Pages](https://pages.github.com).

Install
-------

Ensure [Ruby](https://www.ruby-lang.org/) and [rbenv](https://github.com/rbenv/rbenv) are installed, then:

```
$ make install
```

To start the development server:

```
$ make serve
```

Now browse to [localhost:4000](http://localhost:4000/).

Deploy
------

The blog uses [Github Pages](https://help.github.com/en/articles/about-github-pages-and-jekyll)
for automatic deployment, so it's just matter of:

```
$ git push master
```

Image optimization
------------------

Install `jpegoptim` and `optipng` using your favorite package manager, then:

```
$ make optim
```

License
-------

Contents in `./_posts` are licensed under the terms of the
[Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/).
