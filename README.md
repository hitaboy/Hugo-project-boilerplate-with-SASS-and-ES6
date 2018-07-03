# A boilerplate for Hugo static web generator with webpack, es6 and sass
## Includes a blank theme for [Hugo](http://gohugo.io/), a framework for building websites.

The intent of this theme is to provide a solid starting place for Hugo sites with basic features and include best practices for performance, accessibility, and rapid development.

Features

- Responsive
- Accessible
- Custom Robots.txt (changes values based on environment)
- Internal templates for meta data, google analytics, and DISQUS comments
- RSS Discovery

This theme does not use any CSS library. This will allow you to manipulate the design of the theme totally and is meant to be used in custom frontend development projects.


## Installation

Inside the folder of your Hugo site run:

    $ git clone git@github.com:hitaboy/Hugo-project-boilerplate-with-SASS-and-ES6.git
    $ cd Hugo-project-boilerplate-with-SASS-and-ES6/
    $ cd themes/clean_theme/
    $ yarn

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

## Getting started

After installing the boilerplate successfully it requires just a few more steps to get your site running.

### Configure Hugo

In order to configure your site edit the config.toml

#### Theme
Inside themes there is just one theme calles *clean_theme*
You can modify this one or duplicate it to have a new base and mantain the *clean_theme* as an example.
The theme used for Hugo is defined in config.toml this way
```
theme = "clean_theme"
```

#### Languages
Define desired languages in [languages] block.
You can override default Params for language ( Title, etc... )
```
[languages]
  [languages.en]
    title = "Your new site"
    weight = 1
  [languages.es]
    title = "Tu nuevo sitio"
    weight = 2
```

### Nearly finished

In order to see your site in action, run Hugo's built-in local server.

`$ hugo server`

Now enter [`localhost:1313`](http://localhost:1313/) in the address bar of your browser.

## Production

To run in production (e.g. to have Google Analytics show up), run `HUGO_ENV=production` before your build command. For example:

```
HUGO_ENV=production hugo
```

## Contributing

If you find a bug or have an idea for a feature, feel free to use the [issue tracker](https://github.com/hitaboy/Hugo-project-boilerplate-with-SASS-and-ES6/issues) to let me know.




TODO:

- Document better the options of the template
- Document SASS Structure
