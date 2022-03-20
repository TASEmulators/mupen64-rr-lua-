# Mupen64 Lua

[![Release](https://img.shields.io/github/v/release/TASEmulators/mupen64-rr-lua-?label=Release)](https://github.com/TASEmulators/mupen64-rr-lua-/releases)
[<img src="https://img.shields.io/github/downloads/TASEmulators/mupen64-rr-lua-/total?label=Downloads">]()
[<img src="https://img.shields.io/discord/723573549607944272?label=Discord">](https://discord.gg/bxvZpwdFmW)


[comment]: <> (Second image has to be inline so another approach is used)
[**__\>\> Latest Release \<\<__**](https://github.com/TASEmulators/mupen64-rr-lua-/releases/latest/)<br>

This repository contains the latest source code for continued development of Mupen64 - Nintendo 64 emulator with TAS support, and TASInput plugin. 

This version includes <a href="https://imgur.com/a/SA2CgEB" target="_blank">new Features such as: AVISplit, Reset recording, WiiVC and Backwards Compatibility</a> options all in one.

[comment]: <> ("Thanks a lot markdown for not having open in new feature guess i need html for this smh")
[comment]: <> ("Update: not even this works... This is achievable using kramdown but the github preview renderer doesnt support it so we are stuck with this")


# Building
(This was written having Windows in mind, but it should be possible on Linux as well)
If you want to build Mupen/TASInput on your own, you will need Visual Studio (2017 or 2019 recommended) with C++ packages installed. In repository you will find two solutions files `winproject\mupen64\mupen_2017.sln` and `tasinput_plugin\src\DefDI.sln` used to compile Mupen or TASInput respectively. 

Open either mupen or tasinput solution, on the top you can select Release or Debug build target, press F5 to compile and run with debugger attached. Binaries are placed inside the respective `bin` folder

# Debugging
You can debug Mupen straight away by running it and placing breakpoints in Visual Studio, but since TASInput is a DLL it needs a host application. The .sln is setup in a way that automatically starts mupen (which you need to compile), however you must move the newly compiled TASInput binary **and .pdb file located in the same directory** to the plugins folder (this might be automated in the future)

[comment]: <> (TODO: ADD PROJECT STRUCTURE EXPLANATION)

# Links
Discord: https://discord.gg/eZXbmguKEq<br>
Releases: https://github.com/TASEmulators/mupen64-rr-lua-/releases

