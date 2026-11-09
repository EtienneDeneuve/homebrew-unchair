# homebrew-unchair

Homebrew tap for [Unchair](https://github.com/EtienneDeneuve/unchair).

```bash
brew tap EtienneDeneuve/unchair
brew install --cask unchair
```

The cask installs the notarized Direct-channel DMG from GitHub Releases.
In-app updates use Sparkle (`auto_updates true`).

Bump from the app repo after a release:

```bash
cd ../unchair
./scripts/bump-homebrew-cask.sh <semver>
# then copy Casks/unchair.rb into this tap and push
```
