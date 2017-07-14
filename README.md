# my-setup-mac
My setup kits on MacOSX.


### by App Store

- Kobito
- Microsoft remote desktop
- Dr.Cleaner(US Only) -> no install

### by Homebrew

```shell
$ sh ./install.sh
```

@see [Brewfile](./Brewfile)

[Warning] imagemagick v7 -> v6
```
brew unlink imagemagick
brew uninstall imagemagick
brew install imagemagick@6
brew link imagemagick@6 --force
```

### by Download

- Sophos Anti-Virus
- SourceTree(TODO:Brewfile) -> no install
- anyenv
