local .flatpak
```sh
flatpak-builder --force-clean --install --user build-dir io.github.leuc.igraph-vlk.local.yml
flatpak build-export repo build-dir
flatpak build-bundle repo output.flatpak io.github.leuc.igraph-vlk
```
