# Sphinx Playground

## Install

### uv Python Project Management

``` console
$ curl -LsSf https://astral.sh/uv/install.sh | sh
```

### git

``` console
$ sudo apt install git
$ git clone URL
```

### Initialise project

``` console
$ cd sphinx-playground
$ uv sync

### Create docs
``` console
$ cd docs
$ uv run make html
```

### Open web browser

URL: file:///home/jordan/proj/sphinx-playground/_build/html/index.html
