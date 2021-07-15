# Reinis's blog

Currently available at [reinisc.id.lv](https://reinisc.id.lv/).

A hopefully simple blog. Will likely contain some amount of maths, computation
and maybe even an occasional drawing.

I plan on implementing a small system that allows me to write blog posts in
latex using [tex4ht](https://tug.org/tex4ht/).

## TODO

- [ ] Write the `About me` section
- [ ] Learn to use tex4ht
- [ ] Fill in the blog
  - [ ] Write the first post
- [ ] Integrate utterances
- [ ] Change page styling

## Technologies used

At present, the blog is made with a loose amalgam of the following software:

* [11ty](https://www.11ty.dev/) for putting together the static site content
  * [eleventy-base-blog](https://github.com/11ty/eleventy-base-blog/) serves as
    our main template.
* [actions-gh-pages](https://github.com/peaceiris/actions-gh-pages/) github
  action for deploying the static website to github pages.
