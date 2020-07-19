# Example Site for webcomic theme
I'm using this repo to develop a hugo theme for webcomics. It has also been set up to use [Netlify](https://www.netlifycms.org/) for free deployment and content management. Basically, it's a ready-to-use webcomic site. Just add comics!

## Features/Goals
- [x] set up netlify cms
- [ ] Publish hugo theme for webcomic
  - [x] build templates
    - [x] header
      - [x] hamburger menu of links
      - [ ] graphics in header bar
    - [x] footer with contact info
    - [x] comic display
      - [x] navigation buttons
      - [x] tag display
      - [x] description display
      - [x] show most recent comic on homepage
    - [x] comic archive with links to all comics
      - [x] list of comics
      - [ ] organize list by chapter (tag?)
      - [ ] accordians to hide/show chapters
    - [ ] generic info page with image, title, subtitle, content (basically a blog post)
    - [ ] multi-image info page (for a gallery or cast info page)
  - [ ] Add CSS

## Local Development
Make sure you have the latest version of the theme in the submodule:
```bash
$ cd themes/webcomic theme
$ git pull origin master
```

Then use hugo to serve the site locally:
```bash
$ hugo serve
```

## Deploy with Netlify
This repo has the necessary configuratin and static pages to use Netlify content management system. The files that configure and display Netlify's content management system are located in `static/admin`. To deploy your own copy of this repo:
1. Fork this repo.
2. Create a free Netlify account and follow Netlify's instructions [here](https://www.netlifycms.org/docs/hugo/#deploying-with-netlify) to deploy. 
