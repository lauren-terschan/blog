# My Notes for Updating

### Update cover image

Upload new image as `cover-image.jpg` into `assets/img` folder. No need to delete the one there, it will be replaced if it has the same name. `Add file` >> `Upload file` >> Choose the file >> `Commit`. You may need to try a few times to get the alignment of the image / text as you want it. It will take a few minutes to refresh on the webpage.

These are the same steps for `faivcon.ico`.

### Update site-background color & main text color

Go to `_sass/partials/_config.scss` and update the HEX color at line 33 - `$site-background`. This will update on mobile, tablet, and desktop. Similarly, update `$primary-color` to change the main color of the site.

### Update main navigation tabs

Go to `_config.yml` and scroll to line 21. Add the `title` and the corresponding `url`. New pages will require a new markdown file to be added to the repository.

### Update text-size



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
