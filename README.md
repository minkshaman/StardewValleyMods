Compiling the mods

Installing stable releases from Nexus Mods is recommended for most users. If you really want to compile the mod yourself, read on.

These mods use the crossplatform build config so they can be built on Linux, Mac, and Windows without changes. See the build config documentation for troubleshooting.

Build the project in Visual Studio or MonoDevelop to build it and deploy it to your 'mod' directory in your Stardew Valley installation.

Launching it under the debugger will start Stardew Valley and your mod will be picked up as in the game.
Compiling a mod for release

To package a mod for release:

    Switch to Release build configuration.
    Recompile the mod per the previous section.
    Upload the generated bin/Release/<mod name>-<version>.zip file from the project folder.
