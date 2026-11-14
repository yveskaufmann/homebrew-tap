# yveskaufmann/homebrew-tap

Homebrew tap for my apps.

```sh
brew tap yveskaufmann/tap
brew trust yveskaufmann/tap
brew install --cask hue-lighter
```

| Cask | Description |
| --- | --- |
| [hue-lighter](https://github.com/yveskaufmann/hue-lighter) | Turns Philips Hue lights on at sunset and off at sunrise, logout and shutdown |

Casks are updated automatically by the release workflows of the respective repositories.
The apps are not signed with an Apple Developer ID; installing a cask from this tap removes
the quarantine flag of the installed app.
