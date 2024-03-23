# Virtual Succubus - now without (almost) any issues on macOS!
Like most of you, I really like Virtual Succubus, but I don't have Android device nor Windows PC, so playing it was always some kind of challenge for me. And while getting Virtual Succubus to run on Linux don't take too much effort, on macOS it's pretty different story - beginning with lack of proper Vulkan support and finishing with some crucial bugs in Wine itself. However, after playing around with Wine for a couple of days I've got Virtual Succubus working perfectly on macOS!

Both demo and full release work - this wrapper was tested on M1 MacBook Air 2020 with Virtual Succubus 0.39, however all versions of the game will also work.

This wrapper now features both Intel and Apple Silicon versions - with D3DMetal for Apple Silicon and macOS Sonoma and DXVK for both Intel and Apple Silicon on macOS Ventura and lower.

## Download and install
You'll need Windows version of VS and latest build of this wrapper, which you can download [here](https://github.com/Ferbez/virtual-succubus-macos/releases). Make sure to read all the [instructions](https://github.com/Ferbez/virtual-succubus-macos/blob/main/INSTALLATION.md)!

## Credits
- [Gcenx](https://github.com/Gcenx) for all the work on Wine
- Apple for Game Porting Toolkit
- [SuccuDev](https://www.virtualsuccubus.com) for all his amazing work
