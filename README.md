# This repo is Archived under Pulsar-Edit. As it's now Bunlded into the Core Editor [PR#314](https://github.com/pulsar-edit/pulsar/pull/314)

# Whitespace package

Strips trailing whitespace and adds a trailing newline when an editor is saved.

To disable/enable features for a certain language package, you can use syntax-scoped properties in your `config.cson`. E.g.

```coffee
'.slim.text':
  whitespace:
    removeTrailingWhitespace: false
```

You find the `scope` on top of a grammar package's settings view.

Note: for `.source.jade`, `.source.diff`, `.source.pug` and `.source.patch`, removing trailing whitespace is disabled by default.
