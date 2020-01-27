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

- [Warning] imagemagick v7 -> v6
```
brew unlink imagemagick
brew uninstall imagemagick
brew install imagemagick@6
brew link imagemagick@6 --force
```

- [Warning] mysql v8 -> v5.7

- [Warning] Cask firefox-esr exists in multiple taps
    - Description
    ```
    Error: Cask firefox-esr exists in multiple taps:
    homebrew/cask-versions/firefox-esr
    caskroom/versions/firefox-esr
    Installing firefox-esr has failed!
    ```
    - Cause
    ```
    tap 'caskroom/versions'
    ```
    - How to respond
    ```
    brew untap caskroom/versions
    brew tap homebrew/cask-versions
    ```
    and Comment out "tap 'caskroom/versions'"

### by Download

- Sophos Anti-Virus
- SourceTree(TODO:Brewfile) -> no install
- anyenv
