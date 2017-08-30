
# IMPORTANT

This is an in-development, experimental version of SAP Hybris Techne. It should **NOT** be used for production. Refer to the [Techne website](https://techne.yaas.io) for details about the current version.

> If you are interested in testing beta releases, please contact the [Techne team](mailto:techne@sap.com).

[![Build Status](https://travis-ci.org/SAP/techne.svg?branch=v2.0)](https://travis-ci.org/SAP/techne)

# Getting started

### CDN

Latest minified file is Available via CDN below

```
https://techne.yaas.io/libs/techne/2.0.0-alpha-1/techne.min.css
```
### NPM

Install the library.

````
npm install techne@2.0-alpha-1 --save
````
## Usage

Include the full library.

```html
<link href="node_modules/techne/dist/techne.min.css" rel="stylesheet" />
```

### Stand alone components

The components can be used without loading the whole library. Take a look at the [Available Techne Components](https://github.com/SAP/techne/wiki/Techne-Components) and the individual files at:

```
/dist/components/
```

For example, to use only the cards
```html
<link href="node_modules/techne/components/card.min.css" rel="stylesheet" />
````

# The project

Techne 2.0 is a design system and pattern library package. This project packages the library for `npm` and generates the documentation as a static website.

We rely on several core technologies.

* [Node](https://nodejs.org/) (minimum v6.4)
* Gulp
* Jekyll
* bundle
* Sass
* Nunjucks

## First
In addition to Node, you must have Gulp installed globally:

`npm install -g gulp`

## Gem Dependencies
The following gems will be installed to generate the static documentation site

* Ruby
* Bundle
* Jekyll

## Up and running
Install dev dependencies

`npm install`

## Serve it locally
The documentation website is served from the `docs/_site` directory which is generated by Jekyll. To generate and lunch the documentation site, simply execute the gulp command in terminal at the root of project directory.

`gulp`

# Contributing
New branches should include the type (feature, bug, or hotfix) and the issue number or release number.

```
git checkout -b feature/000
git checkout -b bug/000
git checkout -b hotfix/000
```

Create a pull request against the appropriate branch and assign it for review.

When accepted, the reviewer will merge and delete the branch.
