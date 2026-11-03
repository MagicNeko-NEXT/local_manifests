# PixelOS seventeen local manifest for OnePlus 10T (ovaltine)

Supplementary manifest for `.repo/local_manifests/`. Everything else comes from the PixelOS manifest.

```bash
git clone -b seventeen https://github.com/pixelos-ovaltine/local_manifests .repo/local_manifests
repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```

## Status

The device repos come from the PixelOS 16 `pixelos-a16` work and have not been built on seventeen yet.
`hardware/qcom-caf/sm8450/display` and `hardware/lineage/interfaces` replace the upstream projects and are also
based on Android 16.

## Credits

Based on the work of [MagicNeko-ROM](https://github.com/MagicNeko-ROM), whose device trees and history these repos carry.
