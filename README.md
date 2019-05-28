# OOP and deploy

The source code of the podcast's site [ooprod.ru](https://ooprod.ru).

## Pre requirements

- [Hugo](https://github.com/gohugoio/hugo/releases) (you have to install an extended version with SASS support)
- [podcast-theme](https://github.com/ooprod/podcast-theme) (execute `git submodule update --init` after cloning the repo)

## How to view site locally

Run the next command to run local development server on your machine:

```sh
hugo server
```

## How to add the next episode page

Run the next command:

```sh
hugo new --kind=podcast content\podcast\<name>.md
```

## How to enable CSS debug

Uncomment the next lines in `config.toml`:

```toml
debugCSS = true # show a layout without details
withoutMinification = true
```
