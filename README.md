# Platform Powered

## All together

    $ bundle exec foreman start

## Build it

    $ ruby -run -e httpd . -p 8080

## LiveReload

Load LiveReload in your browser, then run:

    $ bundle exec guard

## Compiling styles

Sass is used to compile styles in `styles` from SCSS to CSS:

    $ bundle exec sass --watch styles:styles/css
