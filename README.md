# harp-gh-pages-boilerplate

The Boilerplate building static sites with [harp](http://harpjs.com/) and publishing to [GitHub Pages](https://pages.github.com/) with [gh-pages npm](https://github.com/tschaub/gh-pages)

## Installation

```
$ git clone
$ mkdir your_static_site
$ cp -r harp-ghpages-boilerplate/{src,package.json,.gitignore} your_static_site/
$ cd your_static_site
$ npm install
$ npm run preview # And open localhost:9000 on your browser
```

## Usage

### Build static site

```
$ npm run compile
```

### Launch preview server on `localhost:9000`

```
$ npm run preview
```

### Publish to gh-pages branch

You should initialize yoru project dir as a repository of GitHub at first.

```
$ npm run publish
```
