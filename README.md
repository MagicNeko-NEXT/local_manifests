# PixelOS seventeen local manifest for OnePlus 10T (ovaltine)

Supplementary manifest for `.repo/local_manifests/`. Everything else comes from the PixelOS manifest.

```bash
git clone -b seventeen https://github.com/MagicNeko-NEXT/local_manifests .repo/local_manifests
repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```

## Status

Targets PixelOS 17 (`seventeen`) on Linux 6.6 (`sm8450-6.6`) for OnePlus 10T (`ovaltine`).
`hardware/qcom-caf/sm8450-6.6/display/hal` and `hardware/lineage/interfaces` replace the upstream LineageOS projects.
The previous Linux 5.10 tree is preserved on `seventeen-5.10`.

## Credits

Based on the work of [MagicNeko-ROM](https://github.com/MagicNeko-ROM), whose device trees and history these repos carry.
