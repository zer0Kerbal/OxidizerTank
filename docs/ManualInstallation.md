---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Oxidizer Tank (MOT)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Oxidizer Tank (MOT)

[Home](./index.md)

**Just when you need that extra oxidizer on your spaceplane...**

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `Mkerb` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Mkerb/OxidizerTank`
* Extract the package's `Mkerb/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/Mkerb` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Mkerb/OxidizerTank`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Mkerb/OxidizerTank`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/Mkerb/OxidizerTank`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [Mkerb]
      + [MkerbInc]
      + [Agencies]
        ...
      + [Flags]
        ...
      ...
    + [OxidizerTank]
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Contracts]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * GPL-3.0.txt
      * ManualInstallation.htm
      * MkerbOxidizerTank.version
      * readme.htm
    ...
    * [ModularManagement (MM)][MM] or [Module Manager][m-m]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Mkerb Inc (MKERB)][MKERB]
* *either*
  * [ModularManagement (MM)][MM]
  * [Module Manager][m-m]

[MKERB]: https://forum.kerbalspaceprogram.com/index.php?/topic/215790-*/ "Mkerb Inc (MKERB)"
[MM]: https://github.com/net-lisias-ksp/ModuleManager "ModularManagement (MM)"
[m-m]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"

<!-- this file CC BY-ND 4.0 by zer0Kerbal -->