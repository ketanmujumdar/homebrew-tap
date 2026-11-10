# ketanmujumdar/tap

Homebrew tap for [secbox](https://github.com/ketanmujumdar/secbox), which runs a project and its AI agent inside a disposable microVM.

```sh
brew install --cask ketanmujumdar/tap/secbox-desktop   # the desktop app, with the CLI
brew install ketanmujumdar/tap/secbox                   # or only the CLI and the daemon
brew services start secbox                              # run the daemon now and at login
```

Apple Silicon Macs only. The formula and cask are written by secbox's release workflow; don't edit them here.
