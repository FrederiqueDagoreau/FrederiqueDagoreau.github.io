# FrederiqueDagoreau.github.io

A [jekyll](https://jekyllrb.com/) [github-pages](https://pages.github.com/) static site.

Github.com will deploy the `/docs` directory from the `main` branch of the repository.

## Requirements

- ruby3.3

## Getting Started

```
git clone git@github.com:FrederiqueDagoreau/FrederiqueDagoreau.github.io.git

cd FrederiqueDagoreau.github.io

bundle install

jekyll build . -d docs

ruby -run -e httpd ./docs [-b IP] [-p PORT]
```

## Making Changes

First, make your changes, then build the jekyll site in `/docs` using:

`jekyll build . -d docs`

Commit your changes to `main`, github.com does the rest.


