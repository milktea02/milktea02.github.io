README:

|Name   | version|
|-------|--------|
|ruby	| v2.7.2p137|
|jekyll | v3.9.0|
|bundler| v2.1.4|

Run locally:

```
bundler exec jekyll serve
```

---

To manage things I used `rbenv` and installed from the `git` repo. Also install the rbenv installer.

I then installed `ruby 2.7.5` since that the the closest version that exists on `rbenv`

`gem` is managed by `rbenv` and used to install both `bundler` and `jekyll`:

```
$ gem install bundler jekyll
```





Migrating from outdate jekyll theme to updated generic minima theme

1. need to move everything from the Front Matter 
  - the `content` section to the section outside of ---

