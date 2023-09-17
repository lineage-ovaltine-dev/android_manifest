```
repo init -u https://github.com/lineage-ovaltine-dev/android_manifest.git -b main

repo sync -j$(nproc) --force-sync -c --no-clone-bundle --no-tags --optimized-fetch --prune
```
