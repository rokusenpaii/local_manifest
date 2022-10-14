```bash
git clone git@github.com:roku-senpai/local_manifest.git --single-branch  --branch=tm .repo/local_manifests 

repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$(nproc --all)
```