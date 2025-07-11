![My *handmade* Roblox Logo](https://github.com/user-attachments/assets/ced623cd-6692-4759-8e46-e9453f5454fc)

<p align="center">
<img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/P0L3NARUBA/roblox-2016-source-code">
<img alt="GitHub Release" src="https://img.shields.io/github/v/release/P0L3NARUBA/roblox-2016-source-code?color=violet">
<img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/P0L3NARUBA/roblox-2016-source-code/master">
</p>

# Roblox 2016 Source Code
This source originates from **[robloxsrc.zip](https://mega.nz/file/mrxkSRRK#n5YmV1iPUPZCfiI6IDWkT3eDq9k3-yA7rl_hURked8Y)** that was spinning around but its hard to find these days.<br>
After a long effort, this repository has been brought to you on github with lots of changes!<br>

**To build from the source, refer to [BUILDING.md](/BUILDING.md)**<br>
   - Make sure to read them properly so you wont face with any issues.

**Having any problems? you can get help at [our discord server](https://www.discord.gg/rVrYHdrbsp) or at the [Issues](https://github.com/P0L3NARUBA/roblox-2016-source-code/issues)**<br>

**Want to play the game in no time? Check out [Releases](https://github.com/P0L3NARUBA/roblox-2016-source-code/releases/)**<br>
**NOTE:** You may need **[Rocknet](https://github.com/P0L3NARUBA/Rocknet/tree/main)** to launch the game.

The **[pixel-lighting](https://github.com/P0L3NARUBA/roblox-2016-source-code/tree/pixel-lighting)** branch is not maintained by me and may be older than the current branch.

# Table of Contents
1. [🪨 Features / Additions](#-features--additions)
2. [📚 Libraries Used](#-libraries-used)
3. [🔨 Tools Used](#-tools-used)
4. [❤️ Contributors / Credits](#%EF%B8%8F-contributors--credits)
5. [🎯 Current Goals](#-current-goals)
6. [⚠️ Current Issues](#%EF%B8%8F-current-issues)

---

## 🪨 Features / Additions
- Added a lot of new features, we're continuing to improve it!
- Fixed issues that breaks the compilation to make every project works like intended.
- Cleaned up the whole source to make things easier and not complicated.
- Changed Splash Screen and Copyright Date(s) just for the sake of it.
- Reverse Engineered some C# libraries and executables using **[ILSpy](/Tools/ILSpy)** to make their source accessible.
- Introducing You **[Rocknet](https://github.com/P0L3NARUBA/Rocknet/tree/main)!** A server made for this particular source.

## 📚 Libraries Used
- [Boost](/Contribs/boost_1_56_0) = 1.56.0
- [cpp-netlib](/Contribs/cpp-netlib-0.11.0-final) = 0.11.0-final
- [DSBaseClasses](/Contribs/DSBaseClasses) = *unknown*
- [OpenSSL](/Contribs/openssl) = 1.0.0c
- [Qt](/BUILDING_CONTRIBS.md) = 4.8.5
- [Roblox SDK](/Contribs/SDK) = *unknown*
- [SDL2](/Contribs/SDL2) = 2.0.4
- [VMProtectWin](/Contribs/VMProtectWin_2.13) = 2.13
- [w3c-libwww](/Contribs/w3c-libwww-5.4.0) = 5.4.0
- [curl](/Contribs/windows/x86/curl/curl-7.43.0) = 7.43.0
- [zlib](/Contribs/windows/x86/zlib/zlib-1.2.8) = 1.2.8
- [glsl-optimizer](/Rendering/ShaderCompiler/glsl-optimizer) = *unknown*
- [hlsl2glslfork](/Rendering/ShaderCompiler/hlsl2glslfork) = *unknown*
- [mojoshader](/Rendering/ShaderCompiler/mojoshader) = *unknown*
- [gSOAP](/RCCService/gSOAP/gsoap-2.7) = 2.7.10
- [RakNet](/Network/raknet) = 5 
- [Mesa](/RCCService/Mesa-7.8.1) = 7.8.1
- [TBB](/TBB_4_1) = 4.1

## 🔨 Tools Used
- [HxD](https://mh-nexus.de/en/downloads.php?product=HxD20)
- [ILSpy](https://github.com/icsharpcode/ILSpy/releases)

---

## ❤️ Contributors / Credits
See **[CONTRIBUTORS.md](/CONTRIBUTORS.md)**

---

## 🎯 Current Goals
- Backporting/Implementing **[Hitius](https://mega.nz/file/DnxUTAgI#52pYMEJyRFMMXVMAU71GboVWYxaTCv25eWB4QHFma6M)**, **[Graphictoria](https://mega.nz/file/e2RU0YbT#tGVrpYqR4fv6z7a4QQcdqT0nbmgdssGm3wGFd9jCiHA)** and **[Economy Simulator](https://mega.nz/file/76AyxJzC#fuKcKHTK6YI5S8zLyelsB7PIt0fVVTsWu9KTrgvXk2E)** Features
   - [x] Color3uint8
     - [x] Color3.fromRGB()
   - [ ] R15
   - [x] :Connect() and :Wait()
- [ ] Fix Keyboard Shortcuts
   - [ ] Reset Character Keybind
   - [ ] Chat Keybind
   - [ ] Windows Key on WindowsClient
- [x] New Fonts
- [ ] Adding Cyrillic & Non-Latin Languages Support
   - [ ] UTF/Unicode Support
   - [ ] Improving Profanity/Swear Filter
- [ ] Adding or Porting New Lua Version
- [x] Supporting Newer Mesh Versions
- [ ] Dark Theme for the Studio
- [ ] Fixing the In-game Recording
- [x] Change the Location of unrelated files inside **content\fonts** folder.
- [ ] Making Bootstrappers don't override our original Roblox files and registries.
   - When this got sorted out, new versions will only include the bootstrappers, so you just have to update the Rocknet in order to upgrade! 
- [ ] Able to compile the source in MacOS(XCode)
   - Needs some configuration, but its actually possible.
- [ ] Able to compile the Android Client
   - We need proper SDK's for this to happen, also needs some work.
- [ ] 64-bit Support for all the projects that listed at the bottom. 
- Building all the projects within the latest Visual Studio Version **[34/68]** 
  - **FYI:** Most of them are never tried so expect some misinformations. 
  - [ ] App
  - [ ] App.BulletPhysics
  - [ ] Base
  - [ ] CoreScriptConverter2
  - [ ] CSG
  - [ ] Log
  - [ ] Network
  - [ ] qtnribbon
    - It gives "Designtime build failed for project" error, seems like it has an easy fix though.
  - [ ] RCCService
  - [ ] RobloxStudio
  - [ ] sgCore
  - [ ] WindowsClient
  #### 3rd Party / Contribs
  - [ ] boost.static
  - [ ] Boost
    - Needs a newer Boost version.
  - [ ] cpp-netlib
  - [x] DSBaseClasses
  - [ ] Curl
     - OpenSSL libraries spits unresolved external symbols so these should get updated too.
  - [ ] Qt
  - [ ] Openssl  
  - [ ] SDL2
    - Windows SDK throws "negative subscript" errors.
  - [x] zlib
  - [ ] w3c-libwww
  - [x] mesa
     - [x] osmesa 
     - [x] gdi
     - [x] glu
     - [x] glut
     - [x] glsl_apps_compile 
     - [x] gears
  #### gSOAP
  - [x] soapcpp2
  - [x] wsdl2h
  #### Rendering
  - [ ] AppDraw
  - [ ] GfxBase
  - [ ] GfxCore
  - [ ] GfxRender
  - [ ] graphics3D
  - [ ] LibOVR
  - [ ] RbxG3D
  #### Shaders
  - [ ] ShaderCompiler
  #### Installer
  - [ ] Bootstrapper
  - [ ] BootstrapperClient
  - [ ] BootstrapperQTStudio
  - [ ] RobloxProxy
  - [x] PrepAllForUpload
  - [x] BootstrapperClient.PrepForUpload
  - [x] BootstrapperRccService.PrepForUpload
  - [x] BootstrapperQTStudio.PrepForUpload
  - [x] RobloxProxy.PrepForUpload
  #### Other
  - [x] IncludeChecker
  - [x] RbxTestHooks
  - [x] ScriptSigner
  - [x] Emcaster
  - [x] EmcasterTest
  - [x] EmReciever
  - [x] Roblox.Common
  - [x] Roblox.Common.Web
  - [x] Roblox.Configuration
  - [x] Roblox.Diagnostics
  - [x] Roblox.Grid.Arbiter.Common
  - [x] Roblox.Grid.Client
  - [x] Roblox.Grid.Common
  - [x] Roblox.Ssh
  - [x] Roblox.System
  - [x] Roblox.WebsiteSettings
  - [x] Roblox.RccServiceArbiter

## ⚠️ Current Issues

- Undo and Redo does not respect proper Color3 values on instances and will instead snap to the nearest BrickColor value.
   - Sometimes Color3 properties could be inaccurate, espicially with BodyColors.

---
