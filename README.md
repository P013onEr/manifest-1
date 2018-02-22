# Pixel Experience #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/P013onEr/manifest-pe -b oreo-mr1

# Sync
repo sync -c -j16 --force-sync --no-clone-bundle --no-tags
```

### Preparing to Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_sagit-userdebug

# Build the code
$ mka bacon -j16
```
