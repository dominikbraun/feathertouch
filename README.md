# Feathertouch

Feathertouch is a light and elegant [verless](github.com/verless/verless) theme.

## Use it

1. [Download the ZIP](https://github.com/dominikbraun/feathertouch/archive/main.zip) and extract it into your project's `themes` directory
or clone this repository into `themes`.
2. Set the page type of your index file to `startpage` (see [Assumptions](#assumptions)).
3. Enable this theme in your `verless.yml`:

```yaml
theme: feathertouch
```

## Assumptions

* By default, Feathertouch expects all your images to be in `/static/img` in your project.
* Feathertouch has an own template for the start page. If you haven't yet, create a top-level `index.md` file inside
your `content` directory and set its page type to `startpage`:

```markdown
---
Type: startpage
---
```
