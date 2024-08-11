
# GiottoData 0.2.15

## Changes
- Bumped _GiottoUtils_ requirements to 0.1.11 for improvements in `package_check()`
- Update `getSODBDataset()`, `listSODBDatasetNames()`, `listSODBDatasetExperimentNames()` to use `package_check()` and include checks for _squidpy_ and _anndata_


# GiottoData 0.2.14 (2024/07/24)

## Bug fixes
- fix `loadSubObjectMini()` loading of image subobjects. [#60](https://github.com/drieslab/GiottoData/issues/60)

## Changes
- code reorganization of mini subobject and mini gobject related functions

# GiottoData 0.2.13 (2024/05/31)

## Changes
- Mini Visium rebuilt for GiottoClass 0.3.2. DWLS results have are also now calculated

# GiottoData 0.2.12.0 (2024/05/22)

## Bug fixes
- fix onload image subobject reconnection when generated from dev directory as opposed to lib directory

## Breaking changes
- `gDataDir()` has been made an internal

## Enhancements
- Additional params can now be passed to `GiottoClass::loadGiotto()` from `loadGiottoMini()` through `...`
- `init_gobject` param for `loadGiottoMini()`

## New
- `generate_mini_subobjects()` for rebuilding the mini subobjects


# GiottoData 0.2.11.0 (2024/05/21)

## Changes
- Mini CosMx rebuilt for GiottoClass 0.3.1
- Mini Visium rebuilt for GiottoClass 0.3.1. Added both the "alignment" and "image" (H&E) images. "image" was also spatially re-aligned
- Mini starmap rebuilt for GiottoClass 0.3.1
