# Personally Developed

A simple, one column theme for [Jekyll](http://jekyllrb.com) that puts your content first.  Extracted from [my blog](jonathanpike.net) for your enjoyment and use. 

![screen shot 2016-02-05 at 8 20 58 am](https://cloud.githubusercontent.com/assets/8129357/12847498/9ed6f2da-cbe1-11e5-9f0a-23d3180613ae.png)

## Usage

#### First Time Jekyll User

Personally Developed is optimized for [GitHub Pages](https://pages.github.com/).  If you don't already have a Jekyll blog on GitHub Pages, simply do the following: 

1. [Fork this repository](https://help.github.com/articles/fork-a-repo/)
2. [Clone the repository](https://help.github.com/articles/cloning-a-repository/) to your local machine
3. Rename the folder to your blog's title
4. Run `bundle install`

Congratulations, you now have a local Jekyll installation that uses Personally Developed!  You can delete the sample content in the `_posts` directory. 

For more information on using Jekyll, please read the [documentation](http://jekyllrb.com/docs/usage/).  See the [GitHub documentation](https://help.github.com/articles/using-jekyll-with-pages/) for using Jekyll with GitHub Pages. 

#### Current Jekyll User

First, make sure you're running Jekyll 2.x, as prior versions did not support Sass.  If so, you'll just have to copy over the following files: 

```
.
├── _includes
|   ├── footer.html
|	├── head.html
|   └── header.html
├── _layouts
|   ├── default.html
|	├── page.html
|   └── post.html
├── _sass
|   ├── neat
|	├── _animate.scss
|	├── _archive.scss
|	├── _fonts.scss
|	├── _footer.scss
|	├── _header.scss
|	├── _layout.scss
|	├── _neat.scss
|	├── _posts.scss
|	├── _reboot.scss
|	├── _syntax.scss
|	├── _utilities.scss
|   └── _variables.scss
├── assets
|   ├── js
|   |	└── main.min.js
├── css
|   └── site.scss
├── archive.html
└── index.html
```

If you're changing from another theme, make sure that the Personally Developed files completely replace any old files you may have in these folders, as other themes may use a similar directory structure.

## Features

A couple of things make Personally Developed a little special : 

- Never get lost again.  The navigation box follows you as you scroll down the page, showing your readers whatever you choose is most important across all pages, all the time. 
- _"Have a great rest of your ____day."_  Thank your readers for viewing your site with a friendly message in the footer. 
- Easy access to the past.  All of your past posts are neatly categorized by year on the archive page. 
- Built-in Google Juice.  The [jekyll-seo-tag](https://github.com/benbalter/jekyll-seo-tag) and [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap) gems automatically make it easy for Google to index your blog. 
- Syntax in style.  Using the beautiful [Solarized](http://ethanschoonover.com/solarized) light colour scheme, your code will shine on the page.


## Customization

Personally Developed can be customized however you'd like.  

Most identity (ie. blog name, author name) config is done in `_config.yml`.  I've included a sample `_config.yml` for you, and you can read more about what you can do with that file in [the Jekyll documentation](http://jekyllrb.com/docs/configuration/).

I've made customization easier with Sass variables! All color options are set right at the top of `_sass/_variables.scss`, as are font defaults.
