# aerc-feedstock

Conda feedstock for [aerc](https://aerc-mail.org).

Builds `linux-64` and `osx-arm64` packages.

## Update procedure

1. Bump `version` in `recipe/recipe.yaml`
2. Update `sha256` (from `curl -L <tarball-url> | sha256sum`)
3. Reset `build.number` to `0` on version bump
4. Commit to `main` — CI builds and uploads to
   [prefix.dev/black-desk](https://prefix.dev/black-desk)
