# Optimus PWA

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.6.

# Get Started
* Site must be SSL e.g. https:// (Firebase hosting is automatic free SSL)
* src/robots.txt must be configured 
* then re-generate src/sitemap.xml by visiting: https://www.xml-sitemaps.com/
* Meta Description and Social media tags rebuilt (see Angular SEO)

## Install Scripts

$ ng new optimus --style=scss --routing=true --prefix=wg
$ ng add @angular/pwa --project optimus

## Optimization Steps:
+ Firebase hosting (firebase init via firebase tools CLI)
+ Bugets set (not for score but for peace of mind)
+ PWA "added"
+ <noscript> tag added
+ <meta name="description"> added
+ Cache-Control set to 1 yr in firebase.json
+ robots.txt added
+ sitemap.xml added
+ ng build --prod --aot

## Resources
[Lighthouse 100](https://dzone.com/articles/angular5-pwa-with-perfect-100-lighthouse-points)
[PWA] (https://blog.angular-university.io/angular-service-worker/)
[Meta Description] (https://yoast.com/meta-descriptions/)
[Angular SEO] (https://www.ganatan.com/tutorials/search-engine-optimization-with-angular)


## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
