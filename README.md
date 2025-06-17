# Jesstern.com

🕺 The homepage of Jesstern Rays.

## Prerequisites

Install Hugo

```sh
brew install hugo
```

## Clone this repository

```sh
git clone git@github.com:jsstrn/jesstern.com.git
```

## Update the current theme as a git submodule

```sh
git submodule update --remote --merge
```

## Clone a new theme as a git submodule

```sh
git submodule add --depth=1 <git-url> themes/<theme-name>
git submodule update --init --recursive
```

## Create new content

```sh
hugo new content/some-page.md
```

## Theme

This site uses the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme by [Aditya Telange](https://github.com/adityatelange/).
