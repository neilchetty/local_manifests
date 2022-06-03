# Download
```bash
# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/neilchetty/local_manifests/RMX3031/twelve.xml --create-dirs
```

# Sync
```bash
repo sync -j$(nproc --all) --force-sync
```