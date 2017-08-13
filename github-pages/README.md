# Github Pages - Project Folder Setup

This is my default setup for creating static websites hosted on Github Pages, with the ability to do more than include pure CSS/HTML, e.g. write Sass and utilize some of Jekyll's capabilities.

I've included two versions: basic and advanced. Both are useful for people who want to write Sass though.

## Basic version

Useful for people who only need Sass; comes with a default `_sass` folder and a very simple config file to tell Jekyll to compile Sass.

## Advanced version

Useful for people who want extreme customization overall, with:
- Multiple custom HTML templates
- Separating HTML into multiple "components"
- Programmatic HTML (e.g. for loops for creating a list of links hosted in `data/`)
- Above-the-fold rendering
- Custom plugins and a deploy script to build from one branch and push to another (GP blocks custom plugins aside from their own, so in order to use them all code needs to be compiled first)

Includes:
- Basic templates for HTML components, e.g. site header/footer, HTML `<head>` information
- Custom config file including useful gems I use personally
- Sass folder setup with folders created for custom files, fonts, images, scripts, etc.
- A [build deploy script](https://github.com/X1011/git-directory-deploy)

## How to install
Just copy everything in either folder, paste it in your desired directory, run `jekyll serve`, go to `localhost:4000` to view your site, and start fiddling around.

If you see any `.keep` files, feel free to delete them at whim.
