# Download
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/neilchetty/local_manifests/RMP2102/twelve.xml --create-dirs
```

# Sync
```bash
repo sync -j$(nproc --all) --force-sync
```
