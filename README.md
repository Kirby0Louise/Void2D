# Void2D Game Engine


Void2D is a powerful, open source 2D game engine based on retro game console architectures and supported on Xbox Scarlett, Windows 10 and Nintendo Switch.

## Usage

Using Void2D is very easy.  Simply download the Visual Studio template of your choice and install it.  Then go to `File -> New Project` and choose the project type for your target platform, give your project a name, and you are good to go.

## Licensing

Void2D is licensed under the Mozilla Public License 2.0 (MPL 2.0).  In short, this means you are free to do whatever you want with the software, including using it in commercial products.  However, you must make the source code of any Void2D files  in any project you use it in available on request.  The full license text can be found in the license file.

Additionally, while not part of the formal license, I ask that you please leave in the "Powered by Void2D Game Engine - By Kirby0Louise" startup screen.  I do not intend to take any credit for what you make using Void2D, but simply would like to use it as an oppertunity to spread awareness of the engine.

## Build Variants

Void2D comes in several different variants, each with distict differences.  The variations are as follows:

#### Void2D High Level

A simplied version of Void2D intended for novice developers as well as projects that do not require use of the more advanced features of the engine.  This is the version that I recommend those new to Void2D use.

- Void2DScarlettHL - Xbox Scarlett compatible version of Void2D High Level
- Void2DWin10HL - Windows 10 compatible version of Void2D High Level
- Void2DNXHL - Nintendo Switch compatible version of Void2D High Level \*

\* *(Note:  This version of Void2D uses OpenGL rather than DirectX.  Additionally, maximum output resolution is capped at 1920x1080p and maximum framerate is capped at 60fps)*

#### Void2D Low Level

The full might of Void2D is unleashed in this version.  Includes support for features disabled in Void2D High Level, such as Render to Texture, Ray Tracing (on supported platforms), direct access to the virtual GPU command queue, FrameFX and more.  Recommended for experienced users as it is easier to break things with it.

- Void2DScarlettLL - Xbox Scarlett compatible version of Void2D Low Level
- Void2DWin10LL - Windows 10 compatible version of Void2D Low Level
- Void2DNXLL - Nintendo Switch compatible version of Void2D Low Level \*

\* *(Note:  This version of Void2D uses OpenGL rather than DirectX.  Additionally, maximum output resolution is capped at 1920x1080p, maximum framerate is capped at 60fps and Ray Tracing is not available)*


## FAQ

#### Where's the support for PlayStation?

PS4/5 development kits are far too expensive for me to obtain (they are in excess of $4000, compared to Switch's $400 and Xbox's $0 dev mode).  Unless someone wants to donate me a couple of PS4/5 devkits, I have no plans to support the platform.  I apologize for any inconvience this may cause.  Talk to Sony about lowering the price of their devkits to something reasonable if you are unhappy.

#### X is/isn't possible on Y hardware, but Void2D's RealRetro is/isn't detecting it

Please submit a bug report and I'll look into it.  Please note that Void2D's RealRetro technology is experimental and is not intended to be an absolute perfect match to the constraints of the target hardware.  While I will try to get as close as reasonably possible, the system will never be perfect.
