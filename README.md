# ilie.io

## Creation

This was created with Hugo by running:

```sh
hugo new site calini.github.io
```

## Adding new themes

You can add themes like such:

```
git submodule add <repo_url> themes/<name>
```

then, modify `theme` under `/config.toml`.

## Adding new posts

```
hugo new posts/<post>.md
```

## Running the server

```
hugo server -D
```