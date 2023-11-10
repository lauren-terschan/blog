# My Notes for Updating

### Update cover image

Upload new image as `cover-image.jpg` into `assets/img` folder. No need to delete the one there, it will be replaced if it has the same name. `Add file` >> `Upload file` >> Choose the file >> `Commit`. You may need to try a few times to get the alignment of the image / text as you want it. It will take a few minutes to refresh on the webpage.

These are the same steps for `faivcon.ico`.

### Update site-background color & main text color

Go to `_sass/partials/_config.scss` and update the HEX color at line 33 - `$site-background`. This will update on mobile, tablet, and desktop. Similarly, update `$primary-color` to change the main color of the site.

### Update main navigation tabs

Go to `_config.yml` and scroll to line 21. Add the `title` and the corresponding `url`. New pages will require a new markdown file to be added to the repository.

### Update text-size

**In a post**: At the beginning of each post, include the following: `<p style="font-size:85%"></p><span class="dropcap"></span>`. If you change this one post down the road, you'll want to go back and update all prior ones so it is consistent.

**On the homepage / posts**: Go to `index.html` > line 15 > `<p style="font-size:80%">` and adjust the percentage.


## Notes from Developer

Long Haul is a minimal jekyll theme built with SASS and focuses on long form blog posts. It is meant to be used as a starting point for a jekyll blog/website.

If you really enjoy Long Haul and want to give me credit somewhere on the internet send or tweet out your experience with Long Haul and tag me [@brianmaierjr](https://twitter.com/brianmaierjr).

#### [View Demo](http://brianmaierjr.com/long-haul)

[![Netlify Status](https://api.netlify.com/api/v1/badges/bd29f13b-3754-46d7-9a39-48db2e174b99/deploy-status)](https://app.netlify.com/sites/long-haul/deploys)

## Features

-   Minimal, Type Focused Design
-   Built with SASS
-   SVG Social Icons
-   Responsive Nav Menu
-   XML Feed for RSS Readers
-   Contact Form via Formspree
-   5 Post Loop with excerpt on Home Page
-   Previous / Next Post Navigation
-   Estimated Reading Time for posts
-   Stylish Drop Cap on posts
-   A Better Type Scale for all devices
-   Comments powered by Disqus
-   [Dark Mode support](https://github.com/brianmaierjr/long-haul/blob/master/preview-dark.png) via [prefers-color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)

## Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Long Haul repo](http://github.com/brianmaierjr/long-haul)
3. Clone it
4. [Install Bundler](http://bundler.io/)
5. Run `bundle install`
6. Run Jekyll Serve and Watch command`bundle exec jekyll serve -w`

## Site Settings

The main settings can be found inside the `_config.yml` file:

-   **title:** title of your site
-   **description:** description of your site
-   **url:** your url
-   **paginate:** the amount of posts displayed on homepage
-   **navigation:** these are the links in the main site navigation
-   **social** diverse social media usernames (optional)
-   **google_analytics** Google Analytics key (optional)

### Header Option

If you'd like your header to be larger then you can use the option below in you `config.yml` to make it take up half of the vertical space on screens 800px wide and up. _Preview image below._

-   **header:** large

![preview Long Haul](/preview-large.png)

## To use on GitHub Pages

To use latest Jekyll and Jekyll Sass Converter on GitHub Pages, <a href="https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/">you can now deploy to a GitHub Pages site using GitHub Actions.</a>

## License

This is [MIT](LICENSE) with no added caveats, so feel free to use this Jekyll theme on your site without linking back to me or using a disclaimer.


# From Posts

### Example Post Formatting

<p class="intro"><span class="dropcap">C</span>urabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Vestibulum id ligula porta felis euismod semper. Donec sed odio dui. Aenean lacinia bibendum nulla sed consectetur.</p>

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<blockquote>Aenean lacinia bibendum nulla sed consectetur. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Cras mattis consectetur purus sit amet fermentum. Nulla vitae elit libero, a pharetra augue. Curabitur blandit tempus porttitor. Donec sed odio dui. Cras mattis consectetur purus sit amet fermentum.</blockquote>

Nullam quis risus eget urna mollis ornare vel eu leo. Cras mattis consectetur purus sit amet fermentum. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.

## Unordered List
* List Item
* Longer List Item
  * Nested List Item
  * Nested Item
* List Item

## Ordered List
1. List Item
2. Longer List Item
    1. Nested OL Item
    2. Another Nested Item
3. List Item

## Definition List
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Maecenas faucibus mollis interdum. Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam.

## Table

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
| Header      | Title       |
| Paragraph   | Text        |

Cras justo odio, dapibus ac facilisis in, egestas eget quam. Curabitur blandit tempus porttitor. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec id elit non mi porta gravida at eget metus. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.

Maecenas faucibus mollis interdum. Maecenas faucibus mollis interdum. Duis mollis, est non commodo luctus, nis


### Featured image

<!-- 
---
layout: post
title:  "Featured Image"
date:   2014-12-14
image: cover-image.jpg
---  
-->

### Post with a code snippet

<p class="intro"><span class="dropcap">Y</span>ou'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes! To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.</p>

Jekyll also offers powerful support for code snippets:

{%- highlight ruby -%}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{%- endhighlight -%}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
