# Release

The project leverages [bumpver][bumpver] to manage versioning of this project.

THe version can be bumped by using the `update` command and specifying the semantic version segment to increment.

```bash
bumpver update --patch  # 1.1.1 -> 1.1.2
bumpver update --minor  # 1.1.1 -> 1.2.0
bumpver update --major  # 1.1.1 -> 2.0.0
```

You can simulate the changes using the `--dry` flag on the `update` command.

```bash
bumpver update --patch --dry
```

The changes and new tag will need to still be manually pushed.

[bumpver]: https://github.com/mbarkhau/bumpver
