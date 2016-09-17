# PKGBUILDs for my Arch Linux packages

## Building

Before deploying a new release, the `PKGBUILD` and `.SRCINFO` need to be updated.

- Update the `PKGBUILD` with the new package version and checksums
- Run `makepkg --printsrcinfo > .SRCINFO`
- Run `git push` to deploy, as usual
