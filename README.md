# Primitive UI + Jekyll

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Please note this is a work in progress. The theme has not been created yet. This is what I am working towards. 

Welcome to your **primitive-jekyll** theme! This is where [Primitive UI](https://taniarascia.github.io/primitive) meets [Jekyll](https://jekyllrb.com/). A front-end design toolkit built with Jekyll & Sass for developing responsive static websites. Primitive also provides helpful, browser-consistent styling for default HTML elements - buttons, forms, tables, lists, and typography.

Demo available: [here](http://cecleeds.github.io/primitive-jekyll/)


## Primitive UI
The original [primitive UI](https://taniarascia.github.io/primitive) and it's [documentation](https://taniarascia.github.io/primitive) is available as a boilerplate/primitive framework for any project and its awesome. The beauty of Primitive is the ease with which you can create unique designs in a beautiful, simple system.

https://github.com/taniarascia/primitive.git

[![primitive-ui on NPM](https://img.shields.io/npm/v/primitive-ui.svg?color=green&label=primitive-ui)](https://www.npmjs.com/package/primitive-ui)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "primitive-jekyll"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: primitive-jekyll
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install primitive-jekyll


> Since [November 2017](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) you can use this theme by adding: `remote_theme: cecleeds/primitive-jekyll` on your `_config.yml` file.


## Usage

### Project tree:
```
Primitive-jekyll    
│
├─── _includes   
|      ├─── author.html
|      ├─── comments.html
|      ├─── date.html
|      ├─── footer.html
|      ├─── header.html
|      ├─── navbar.html
│      └─── share.html
├─── _layouts
│      ├─── compress.html
│      ├─── default.html
│      ├─── home.html
│      └─── post.html
├─── pages
├─── _posts
│
├─── _sass
│      ├─── _author.scss
│      ├─── _cards.scss
│      ├─── _navbar.scss
│      ├─── _post.scss
│      ├─── _syntax.scss
│      ├─── _tags.scss
│      └─── _variables.html
└─── assets
     │
     └─── css
     │    └─── main.scss
     └─── img
     │    └─── icons
     └─── js
          ├─── init.js
          └─── vendor
```

Now you can begin modifying variables in `variables.scss`. This file will define your colors, typography, sizes, breakpoints, buttons, borders, and more. Define all your variables here to keep your project organized.

You can view `dist/test.html` or `docs/template.html` to see some example elements as you make changes.

This gem offers some *main* layouts that can be used/edited:
- The `_layouts/default.html`, is the skeleton of the pages, where header,footer, assets are called. It should be used in most of the other layouts,
- The `_layouts/home.html` is the main layout the will be your home, where your blog posts will be shown;
- The `_layouts/post.html` is the layout used to present the blog posts themselves, where they will be rendered.

Inside the `_includes/` directory there are the partials that are used inside the layouts.

The stylesheets of this gem can be edited both in `_sass/` and in `assets/css/main.scss`.
The main colors of the theme can be found and customized in `_sass/variables.scss`.

To edit the current JavaScript functions of the gem, the file you are looking for is in `assets/js/init.js`.

Your blog posts (`*.md` files) should be put in the `_posts` directory.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cecleeds/primitive-jekyll. This project is welcomes collaboration, but contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## Credits

This theme was inspired by [Tania Rascia](https://www.taniarascia.com). Tania also credits Dave Gamache for building [Skeleton CSS](http://getskeleton.com/), the original inspiration for building Primitive and understanding responsive CSS.


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).


