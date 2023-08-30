# WALLSEC Blog

### Writing posts locally

Install ruby and bundler for your operating system.
On the first run install Jekyll dependencies:

```console
bundle config path 'vendor/bundle' --local
bundle install
```

In case you want to update depencencies execute (you should do that before writing a new post):

```console
bundle update
```

Afterwards, execute ``bundle exec jekyll serve --livereload``.
All changes will be reloaded immediately after saving Markdown files in ``_posts`` directory.

### Name conventions

