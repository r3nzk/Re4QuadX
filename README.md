# QuadX

Standalone Modding tool made to edit Resident Evil 4 (2005) data, enemy and map/level files within a 3D viewport.

[![Github license](https://img.shields.io/github/license/r3nzk/Re4QuadX.svg)](LICENSE) 
[![GitHub release](https://img.shields.io/github/release/r3nzk/Re4QuadX.svg)](https://github.com/r3nzk/Re4QuadX-Project//releases/latest)
[![Github All Releases](https://img.shields.io/github/downloads/r3nzk/Re4QuadX/total.svg)](https://github.com/r3nzk/Re4QuadX/releases/latest)

> [!NOTE]
This version is not being actively worked on for now, as I am supporting [JADERLINK](https://github.com/JADERLINK/) on the next version of the original Quad editor. Once the new version is released, I will re-fork it and keep the active development. This version is still fully usable as it is, just don’t expect new features anytime soon. (You will get an alert in editor when the new ver. is released).

## About:
QuadX is a 3D editor made to modify core files for most versions of OG RE4. It features a 3D viewport for real-time object manipulation.
This fork focuses on improving editing workflow, adding more interactions, themes and automation.

<img width="1919" height="1056" alt="example1" src="https://github.com/user-attachments/assets/b459dc5a-12aa-4a01-8db5-0b05e7f45a45" />

## Fork Upgrades
* General interface/logic/structure rework with modern components and intuitive visual style.
* Renderer mipmap generation and new render loop for smoother 3D view.
* Gizmo based object translation and rotation supporting local and worldspace manipulation.
* Built-in automation to extract, import and repack entire room files in 1 click.
* Console tab that displays editor actions with deeper setup logs and sanity checks.
* Search and Filter bars to multiple panels for easier element selection (WIP).
* Dark and Light theme support.
* Auto update checker at startup.
* More options and preferences.

Check full changelog [here](https://github.com/r3nzk/RE4QuadX/commits/main).

## Usage
This editor is designed to be as intuitive and straightforward as possible. However, since it works with closed-source 2005 game, some of RE4’s file formats, structures, or engine quirks can be a bit unclear for beginners. If you need guidance, you can check the project [Wiki](https://github.com/r3nzk/Re4QuadX/wiki) for basic setup instructions and some general usage tips.

To use the program properly, you will need the original game files of your target version. You can follow the step-by-step Setup Wizard that runs on first launch (or open it anytime from Misc > Setup Wizard). It will help you configure all required game directories and tool paths.

## Supported Versions
Currently supports (same as RE4QuadNewAge):
- Resident Evil 4 Ultimate HD Edition (UHD)
- Resident Evil 4 Sourcenext/Ubisoft (2007)
- Resident Evil 4 for Playstation 2
- Resident Evil 4 for Playstation 4/Nintendo Switch (Partially)

## Libraries/Packages Utilized
* [JADERLINK_MODEL_VIEWER](https://github.com/JADERLINK/JADERLINK_MODEL_VIEWER)
* [TGASharpLib](https://github.com/ALEXGREENALEX/TGASharpLib)
* [DDSReaderSharp](https://github.com/ALEXGREENALEX/DDSReaderSharp)
* [ScarletLibrary](https://github.com/xdanieldzd/Scarlet)
* [Newtonsoft Json.NET](https://www.newtonsoft.com/json)
* [OpenTK](https://www.nuget.org/packages/OpenTK/)
* [OpenTK.GLControl](https://www.nuget.org/packages/OpenTK.GLControl)
* [PowerLib.Winform](https://www.nuget.org/packages/PowerLib.Winform)
* [RealTaiizor](https://github.com/Taiizor/ReaLTaiizor)

## Credits
QuadX is only a fork of [RE4QuadNewAge](https://github.com/JADERLINK/Re4QuadNewAge) Editor created by [JADERLINK](https://github.com/JADERLINK/).
Most of the heavy lifting, research, and reverse-engineering work were done by him and the RE4 modding community.
This fork mainly focuses on improving usability, adding quality-of-life features, and modernizing the interface with more options and themes, while keeping the original core and logic built entirely by jaderlink.

## License
MIT License – Free to use, modify, and distribute.
