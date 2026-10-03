# nixos-assets

Large binary assets for [nixos-config](https://github.com/Botchi24/nixos-config),
used there as the non-flake input `assets`.

- `wallpapers/` — images for wallpaper-daemon (rotated every 5 minutes)
- `fastfetch-profiles/` — logos fastfetch-random picks from

After changing anything here: commit, push, then in nixos-config run
`nix flake update assets` and rebuild.
