# Void2D Game Engine


Void2D is a powerful, open source 2D game engine based on retro game console architectures and supported on Xbox Series X|S, Windows 10 and Nintendo Switch.

## Usage

Using Void2D is very easy.  Simply download the Visual Studio template of your choice and install it.  Then go to `File -> New Project` and choose the project type for your target platform, give your project a name, and you are good to go.

## Licensing

Void2D is licensed under the Mozilla Public License 2.0 (MPL 2.0).  In short, this means you are free to do whatever you want with the software, including using it in commercial products.  However, you must make the source code of any Void2D files  in any project you use it in available on request.  The full license text can be found in the license file.

Additionally, while not part of the formal license, I ask that you please leave in the "Powered by Void2D Game Engine - By Kirby0Louise" startup screen.  I do not intend to take any credit for what you make using Void2D, but simply would like to use it as an oppertunity to spread awareness of the engine.

## Features

Void2D contains a wide variety of features.  I have listed just a few of them here.  You can read more in depth about these and others on the wiki.

- Powerful 2D graphics engine that squeezes everything it can from your GPU and CPU.
- Full DirectX 12 Ultimate support
- Support for up to 7680x4320p (8K) resolution and 120fps
- HDR10 and Dobly Vision 12-bit HDR support
- Retro console esque architecture, easy to learn and very flexible
- RealRetro technology, a feature that allows you to accurately simulate the limitations of actual game consoles of the past
- Ray Tracing
- Nvidia DLSS 2
- AMD FidelityFX Super Resolution
- DirectML Super Resolution
- FrameFX, a powerful, assembly like scripting language that allows you to create beautiful effects over your final rendered image
- Render to Texture, allowing you to render an image normally and then use that image as an object in the final rendered result
- Cross platform support for Xbox Series X|S, Windows 10 and Nintendo Switch

## Build Variants

Void2D comes in several different variants, each with distict differences.  The variations are as follows:

#### Void2D High Level

A simplied version of Void2D intended for novice developers as well as projects that do not require use of the more advanced features of the engine.  This is the version that I recommend those new to Void2D use.

- Void2DXSerHL - Xbox Series X|S compatible version of Void2D High Level
- Void2DWin10HL - Windows 10 compatible version of Void2D High Level
- Void2DNXHL - Nintendo Switch compatible version of Void2D High Level \*

\* *(Note:  This version of Void2D uses Vulkan rather than DirectX.  Additionally, maximum output resolution is capped at 1920x1080p and maximum output framerate is capped at 60fps)*

#### Void2D Low Level

The full might of Void2D is unleashed in this version.  Includes support for features disabled in Void2D High Level, such as Render to Texture, Ray Tracing (on supported platforms), direct access to the virtual GPU command queue, FrameFX and more.  Recommended for experienced users as it is easier to break things with it.

- Void2DXSerLL - Xbox Series X|S compatible version of Void2D Low Level
- Void2DWin10LL - Windows 10 compatible version of Void2D Low Level
- Void2DNXLL - Nintendo Switch compatible version of Void2D Low Level \*

\* *(Note:  This version of Void2D uses Vulkan rather than DirectX.  Additionally, maximum output resolution is capped at 1920x1080p, maximum output framerate is capped at 60fps and Ray Tracing is not available)*


## FAQ

#### Where's the support for PlayStation?

PS4/5 development kits are far too expensive for me to obtain (they are in excess of $4000, compared to Switch's $400 and Xbox's $0 dev mode).  Unless someone wants to donate me a couple of PS4/5 devkits, I have no plans to support the platform.  I apologize for any inconvience this may cause.  Talk to Sony about lowering the price of their devkits to something reasonable if you are unhappy.  You are of course free to make your own PS4/5 fork of Void2D, as long as it remains open source.  If I do manage to get my hands on some PS4/5 devkits I may even use your code in the main branch, and of course you will be fully credited.

#### What do you mean by "retro console esque architecture"?

Void2D draws two different types of images to the final render result, Sprites and Background Layers.  With one exception, these images consist of 8x8 tiles from TVRAM, arranged as determined by the developer.  This is similar to how consoles such as the NES, Master System, SNES and Genesis worked.  Void2D also shares some similarities to consoles such as the Sega Saturn and N64, such as their ability to draw quads and perform framebuffer effects.  Hence why it has a "retro console esque architecture".

#### X is/isn't possible on Y hardware, but Void2D's RealRetro is/isn't detecting it

Please submit a bug report and I'll look into it.  Please note that Void2D's RealRetro technology is experimental and is not intended to be an absolute perfect match to the constraints of the target hardware.  While I will try to get as close as reasonably possible, the system will never be perfect.

#### Are you actually going to ever release this?

Yes, and Void2D (as well as Void3D) are both WIP projects that I do at my own pace in my free time.  Engines take a long time to develop even with professional, paid teams of engineers, let alone a single college student developing as a hobby in their free time.  It will likely be years before the first release comes out.

#### Is Louise cute?

Yes!  Absolutely!
