# homebrew-unchair

Homebrew tap for [Unchair](https://github.com/EtienneDeneuve/unchair).

```bash
brew install --cask EtienneDeneuve/unchair/unchair
```

The fully-qualified install command auto-taps this repository and trusts only the selected cask. The cask installs the signed, notarized Direct-channel DMG from GitHub Releases.

In-app updates use Sparkle (`auto_updates true`). Homebrew users can also run:

```bash
brew upgrade --cask EtienneDeneuve/unchair/unchair
```

Bump from the app repo after a release:

```bash
cd ../unchair
./scripts/bump-homebrew-cask.sh <semver>
# release.sh publishes the generated cask here automatically via gh api
```
