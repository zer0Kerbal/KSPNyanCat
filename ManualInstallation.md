---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.1.0
NyanCat (NCAT)
created: 01 Apr 2019
updated: 01 Apr 2022 -->

<!-- based upon work by Lisias -->

# NyanCat (NCAT)

A nyan cat add-on for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/NyanCat`
* Extract the package's `NyanCat/` folder into your KSP's as follows:
  * `<PACKAGE>/SimpleConstruction` --> `<KSP_ROOT>/GameData/NyanCat`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/NyanCat`
* Extract the package's `GameData/NyanCat` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/NyanCat` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```
<KSP_ROOT>
  [GameData]
    [godarklight]
      [NyanCat]
        [Plugins]
          NyanCat.dll
          nyan.ogg
          ...
        1.1.0.0.htm
        changelog.md
        NyanCat.version
        SimpleBSD.txt
        readme.htm
      ...
  KSP.log
  ...
```

### Dependencies

* none
