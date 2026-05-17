# gettxoutsetinfo.com

A static GitHub Pages site for `gettxoutsetinfo.com`, built around Bitcoin
Core's `gettxoutsetinfo` RPC.

Temporary GitHub Pages URL:

```text
https://scgbckbone.github.io/txoutinfo-page/
```

## Local preview

Open `index.html` directly in a browser, or serve the directory with any static
file server.

## Git notes

This workspace has a read-only `.git` mountpoint, so the repository metadata was
initialized in `.repo` instead:

```sh
git --git-dir=.repo --work-tree=. status
```

On a normal checkout, `git init` will create the usual `.git` directory.
