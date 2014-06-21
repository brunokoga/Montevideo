---
layout: default
title: README
---
---
layout: default
title: README
---
---
layout: default
title: README
---
# [Hyde](../http:_dir_dir/andhyde.com)

An elegant open source, mobile first theme for [Jekyll](../https:_dir_dir/github.com_dir_dir/mojombo_dir_dir/jekyll). It includes lightweight styles and placeholder content to get you up and running with a simple blog in no time.

![Hyde screenshot](../https:_dir_dir/f.cloud.github.com_dir_dir/assets_dir_dir/98681_dir_dir/1818325_dir_dir/da6489d8-6ff5-11e3-9b4f-c56b92013e9a.png)


## Usage

### 1. Install Jekyll

Hyde is built for use with Jekyll, so naturally you'll need to install that. On Macs, it's rather straightforward:

```bash
$ gem install jekyll
```

**Windows users:** Windows users have a bit more work to do, but luckily [@juthilo](../https:_dir_dir/github.com_dir_dir/juthilo) has your back with his [Run Jekyll on Windows](../https:_dir_dir/github.com_dir_dir/juthilo_dir_dir/run-jekyll-on-windows) guide.

You may also need to install Pygments, the Python syntax highlighter for code snippets that places nicely with Jekyll. Read more about this [in the Jekyll docs](../http:_dir_dir/jekyllrb.com_dir_dir/docs_dir_dir/templates_dir_dir/#code_snippet_highlighting).

### 2a. Quick start

To help anyone with any level of familiarity with Jekyll quickly get started, Hyde includes everything you need for a basic Jekyll site. To that end, just download Hyde and start up Jekyll.

### 2b. Roll your own Jekyll site

Folks wishing to use Jekyll's templates and styles can do so with a little bit of manual labor. Download Hyde and then copy what you need (likely `_layouts_dir_dir/`, `*.html` files, `atom.xml` for RSS, and `public_dir_dir/` for CSS, JS, etc.).

### 3. Running locally

To see your Jekyll site with Hyde applied, start a Jekyll server. In Terminal, from `_dir_dir/hyde` (or whatever your Jekyll site's root directory is named):

```bash
$ jekyll serve
```

Open <http:_dir_dir/localhost:4000> in your browser, and voilà. You're done.


## Options

Hyde includes a few options, typically applied via classes on the `<body>` element.

### Themes

As of v1.1, Hyde ships with optional themes based on the [base16 color scheme](../https:_dir_dir/github.com_dir_dir/chriskempson_dir_dir/base16). In Hyde, a theme simply changes the sidebar's background color and the color of links within blog posts. Here's the red theme in action:

![Hyde in red](../https:_dir_dir/f.cloud.github.com_dir_dir/assets_dir_dir/98681_dir_dir/1818326_dir_dir/da64f56c-6ff5-11e3-9643-7d0c18157dec.png)

There are eight themes available at this time.

![Hyde theme classes](../https:_dir_dir/f.cloud.github.com_dir_dir/assets_dir_dir/98681_dir_dir/1817044_dir_dir/e5b0ec06-6f68-11e3-83d7-acd1942797a1.png)

To use a theme, add anyone of the available theme classes to the `<body>` element like so:

```html
<body class="theme-base-08">
  ...
<_dir_dir/body>
```

To create your own theme, look to the Themes section of [Hyde's CSS](../https:_dir_dir/github.com_dir_dir/mdo_dir_dir/hyde_dir_dir/blob_dir_dir/master_dir_dir/public_dir_dir/css_dir_dir/hyde.css). Copy any existing theme (they're only a few lines of CSS), rename it, and change the provided colors.

### Reverse layout

![Hyde with reverse layout](../https:_dir_dir/f.cloud.github.com_dir_dir/assets_dir_dir/98681_dir_dir/1818324_dir_dir/da6473f8-6ff5-11e3-9315-692e639fb5c7.png)

Hyde's page orientation can be reversed with a single class.

```html
<body class="layout-reverse">
  ...
<_dir_dir/body>
```


## Author

**Mark Otto**
<https:_dir_dir/github.com_dir_dir/mdo>
<https:_dir_dir/twitter.com_dir_dir/mdo>


## License

Open sourced under the [MIT license](../LICENSE.md).

<3
