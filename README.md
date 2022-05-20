# Github page

My Github page is in construction...

## Quick description

This repository contains the structure for my [Github page](https://audrey-onfroy.github.io). I followed [this tutorial](https://www.youtube.com/watch?v=LIFvgrRxdt4) to build two repositories :

* **blog** (here) contains the structure for my [Github page](https://audrey-onfroy.github.io) and is built with [hugo](https://gohugo.io/)
* **audrey-onfroy.github.io** repositories is built as a submodule of the public directory in **blog**

## Some helpful command

* visualize the website with localhost :

```bash
hugo server -D
```

* compile the site in the public directory :

```bash
hugo -t *theme_name*
```

* add a new post :

```bash
hugo new posts/post_name.md
```