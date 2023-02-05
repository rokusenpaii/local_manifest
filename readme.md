```bash
git clone https://github.com/rokusenpaii/local_manifest.git --single-branch  --branch=sweet .repo/local_manifests 
```
or

```bash
git clone git@github.com:rokusenpaii/local_manifest.git --single-branch  --branch=sweet .repo/local_manifests 
```

```bash
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$(nproc --all)
```