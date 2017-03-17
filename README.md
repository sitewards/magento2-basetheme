# magento2-basetheme

## Installation

1. Go to the magento project root
2. Run `composer require sitewards/magento2-basetheme`
3. Run `bin/magento setup:upgrade`
4. If you are not in developer mode you should run `bin/magento setup:static-content:deploy`
5. Go to `vendor/snowdog/frontools`
6. Run `npm install`
7. Run `gulp setup` and `gulp styles`

## Roadmap

- Pattern Lib for documentation of our base theme

- General styles
    - apply our variables for brand etc
    - write mixins for style combinations
    - write mixins for applying font styles
    - add vertical spacing rhythm
    - z-index map [organizing-z-index-with-sass](https://jonsuh.com/blog/organizing-z-index-with-sass/)
    - replace icons with font awesome

- topbar
    - replace link navigation with `nav`
    - remove welcome message from the nav
    - refactor html css classes to BEM

- footer
    - refactor html, navigations should be `nav` tag
    - add column for payment, delivery, whatever else we use
    - refactor classes to BEM style
    
- navigation
    - refactor classes to BEM style
    
- buttons
    - make button classes and styles consistent
    - refactor class namings to BEM 

- checkout

- cart
    - refactor table to be better responsive

- account
    - dashboard navigation should be `nav` tag