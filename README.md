# DRH Mod Index

The mods [DRH Launcher](https://github.com/Tutez64/DRH-Launcher) offers for [Dungeon Rampage Haxe](https://github.com/Tutez64/Dungeon-Rampage-Haxe). It points to each version's zip, a release asset of the mod's own repository; it holds no mod.

## Submitting a version

Not open yet: the launcher commands that write and submit an entry are not released.

One file per version, `mods/<id>/<version>.json`. `--pack-mod` writes it with the release, `--submit-mod` opens the pull request. The CI checks it, then it is reviewed against the previous version. The rules are in [Index entry](https://github.com/Tutez64/Dungeon-Rampage-Haxe/blob/master/docs/modding.md#index-entry); how to make a mod, in [Making a mod](https://github.com/Tutez64/Dungeon-Rampage-Haxe/blob/master/docs/making-a-mod.md).

## Reading the index

Every entry, generated on each merge: `https://tutez64.github.io/DRH-Mod-Index/index.json`. Its format is in [Index entry](https://github.com/Tutez64/Dungeon-Rampage-Haxe/blob/master/docs/modding.md#index-entry).

## License

The entries and `index.json` are under [CC BY 4.0](LICENSE): reuse them, crediting the DRH Mod Index and, for its texts, each entry's `author`. Submitting an entry publishes it under that license, its texts included. The CI's code will be under GPLv3.
