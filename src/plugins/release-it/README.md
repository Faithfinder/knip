# Release It

## Enabled

This plugin is enabled when any of the following packages is in `dependencies` or `devDependencies`:

- release-it

## Default configuration

```json
{
  "release-it": {
    "config": [".release-it.json", ".release-it.{js,cjs}", ".release-it.{yml,yaml}", "package.json"]
  }
}
```

Also see [Knip plugins][1] for more information about plugins.

[1]: https://github.com/webpro/knip/blob/next/README.md#plugins