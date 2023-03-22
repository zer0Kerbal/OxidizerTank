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

To install, place the `OxidizerTank` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/OxidizerTank`
* Extract the package's `OxidizerTank/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/OxidizerTank` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/OxidizerTank`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/OxidizerTank`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/OxidizerTank`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [OxidizerTank]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      + [Plugins]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * ManualInstallation.htm
      * changelog.md
      * License.txt
      * readme.htm
      * OxidizerTank.version
    ...
    * [Module Manager /L][mml] or [Module Manager][mm]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [SimpleConstruction! (SCON)][SC]
* *either*
  * [Module Manager][mm]
  * [Module Manager /L][mml]

[SC]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-*/ "SimpleConstruction! (SCON)"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"

<!-- this file CC BY-ND 4.0 by zer0Kerbal -->