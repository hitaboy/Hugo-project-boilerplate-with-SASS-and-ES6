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

    $ cd themes
    $ git clone https://github.com:hitaboy/Hugo-project-boilerplate-with-SASS-and-ES6.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Getting started

After installing the boilerplate successfully it requires just a few more steps to get your site running.

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
