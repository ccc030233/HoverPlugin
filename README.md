# HoverPlugin

Unreal Engine 4 plug-in with hover effect components.


## About

This Unreal Engine 4 plug-in shows how to convert a BP component to a C++
component as presented by Zak Parrish and Gerke Max Preussner during the
live coding demonstration at GDCE Europe 2015. It accompanies the corresponding
[presentation slides](https://headcrash.industries/vault/presentations/gdc-europe/)


## Supported Platforms

This plug-in was last built against **Unreal Engine 4.9** and should work on
all platforms.


## Dependencies

This plug-in requires Visual Studio and either a C++ code project or a the full
Unreal Engine 4 source code from GitHub. If you are new to programming in UE4,
please see the official [Programming Guide](https://docs.unrealengine.com/latest/INT/Programming/index.html)!


## Usage

You can use this plug-in as a project plug-in, or an Engine plug-in.

If you use it as a project plug-in, clone this repository into your project's
*/Plugins* directory and compile your game in Visual Studio. A C++ code project
is required for this to work.

If you use it as an Engine plug-in, clone this repository into the
*/Engine/Plugins/Media* directory and compile your game. Full Unreal Engine 4
source code from GitHub (4.9 or higher) is required for this to work.

In order to use the Blueprint version of the hover component, copy the file
*/Content/BlueprintHoverComponent.uasset* into your project's */Content* directory.


## Support

Please [file an issue](https://github.com/ue4plugins/HoverPlugin/issues), submit a
[pull request](https://github.com/ue4plugins/HoverPlugin/pulls?q=is%3Aopen+is%3Apr)
or email us at info@headcrash.industries


## References

* [Unreal Engine Forum Thread](https://forums.unrealengine.com/showthread.php?81573-GDCE-2015-Blueprint-Components-to-C)