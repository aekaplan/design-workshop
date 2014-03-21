## Modern Web Design Workshop

By [Adam Kaplan](http://adamkaplan.me) and [Stephanie Briones](http://stephaniebriones.com/)

In this three part workshop, we're going to be covering the basics of building a mobile first responsive layout, applying
simple visual design and selecting typefaces for the web. For our project, we will be creating a blog using
[Jekyll](http://jekyllrb.com).

## Schedule

####Friday, March 21
In our first workshop, we will cover setting up a blog using [Jekyll](http://jekyllrb.com) and adding the foundation of our mobile first layout.

####Friday, March 28
In part two of our workshop, we will continue to refine our mobile first layout, focus on working with web type and discuss
how to best use color on the web.

####Friday, April 4
In our last workshop, we will take a closer look at the details of our design and explain how you can easily host your blog
on [GitHub Pages](http://pages.github.com).

## Requirements
* Laptop running Linux, Unix, or Mac OS X
* Ruby and Git Installed
* GitHub Account
* Text Editor (TextMate, Sublime, VIM)

## Resources
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [Git](http://git-scm.com/downloads)
* [Jekyll](http://jekyllrb.com/docs/installation/)
* [GitHub Pages](http://pages.github.com).
* [Liquid](https://github.com/Shopify/liquid/wiki)
* [Markdown Basics](https://help.github.com/articles/markdown-basics)
* [Normalize.css](http://necolas.github.io/normalize.css/)
* [Mobile first responsive design](http://www.adamkaplan.me/grid/)

## Setup Jekyll

#### Create a new repo
```
yourusername.github.io
```

#### Clone the repo
```
git clone git@github.com:yourusername/yourusername.github.io.git
```

#### Change directories
```
cd yourusername.github.io
```

#### Install Jekyll
```
gem install jekyll
```

#### Create new blog
```
jekyll new blog
```

#### Move directory
```
mv blog/* ./
```

#### Delete blog folder
```
rm -rf blog
```

#### Start the server
```
jekyll serve -w
```

#### Visit
```
localhost:4000
```
