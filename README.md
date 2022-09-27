# local_manifest
Local manifests used for building Android custom ROMs for Xiaomi Redmi 9A `(dandelion)`
```
git clone https://github.com/alternoegraha/local_manifest.git .repo/local_manifests
```
**(LineageOS only)** apply monet (dynamic color theme) engine patch:
```
patch -d frameworks/base -p1 < .repo/manifests/patches/0021-monet-Fix-overly-low-chroma-for-tones-below-90.patch
```
NOTE: main `master` branch is only used if you have your own build server. if you using buildbots, check this repo branches.