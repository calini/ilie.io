# ilie.io

#### TODO

- [X] Hugo
- [X] Dark mode theme
- [ ] Custom theme
- [ ] Analytics
- [ ] Start posting


## Tasks

### Gen

This was generated with Hugo by running:

```sh
hugo new site calini.github.io
```

### Add Theme

Adding new themes

You can add themes like such:

```
git submodule add <repo_url> themes/<name>
```

then, modify `theme` under `/config.toml`.

### New Post

Adding new posts

```
hugo new posts/<post>.md
```

### Run

Running the server locally

```
hugo server -D
```

### Build

Building the website
```
hugo
```

### Get 

Get [Hugo](https://github.com/gohugoio/hugo)

```
go install github.com/gohugoio/hugo@latest
```

### Pull

Pull themes locally

```
git submodule update --init --recursive
```

### Update

Update themes to their last version

```
git submodule update --remote --merge
```