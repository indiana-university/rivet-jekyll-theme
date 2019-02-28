# rivet-jekyll-theme

This repository holds the code for a [Rivet](http://rivet.iu.edu)/[Rivet Shell](https://rivet.iu.edu/add-ons/rivet-shell/) theme for use in GitHub Pages or Jekyll.

## Use the theme:

### 1. Gemfile

Add the following to your Gemfile in your Jekyll site:
    
```
gem "rivet-jekyll-theme", :git => "git://github.com/indiana-university/rivet-jekyll-theme.git"
```

### 2. _config.yml

In your `_config.yml` file, replace the `theme` property value with `rivet-jekyll-theme`:

```
theme: rivet-jekyll-theme
```

### 3. Bundle

You'll also need to run `bundle install` to download the theme like adding any Gem.

## TODOs

 * Includes (`_includes`) for: 
    * styles area
    * scripts area (after footer)
    * HEAD metadata from front-matter (tags, categories, title, description, keywords, etc.)
    * Header
    * Footer
    
* Publish as a Gem

## Links
 * [Rivet Source Code](https://github.com/indiana-university/rivet-source)

