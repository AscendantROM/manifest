To initialize your local repository, use this command:

	repo init -u https://github.com/AscendantROM/manifest.git -b eleven-staging

 Then to sync up:

```bash
repo sync --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

Build Ascendant
==================

```bash
source build/envsetup.sh

lunch ascendant_codename-buildtype

mka ascendant
```
Credits
==================
Special thanks to the following ROMs for making ascendant possible:

- Descendant
- POSP
- Project Fluid
