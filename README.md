# Waffleparty marketplace

The plugin catalog for waffleparty. It holds no plugin code: each entry points at a plugin's own repository, pinned to a release tag.

| Plugin | Repository |
| --- | --- |
| `waffle` | [waffleparty/waffle](https://github.com/waffleparty/waffle) |

## Use

Claude Code:

```text
/plugin marketplace add waffleparty/marketplace
/plugin install waffle@waffleparty
```

## Updates

A plugin's release workflow opens a pull request here that moves its entry's `source.ref` and `version` to the new tag. Tags have no `v` prefix (`1.4.0`).

An entry with no `ref` follows the plugin repository's default branch. `waffle` has no `ref` until its first release.

## License

MIT
