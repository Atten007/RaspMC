# RaspMC
RaspMC is a completely free Minecraft server software that currently only works on all the 64-bit Raspberry Pi.
I've written this software in Python 3.11 and it's also backwards-compatible until Python 3.6.8.
The software does also support the deprecated Python 2, but only the very old Minecraft versions beginning with 1.2.5 until 1.8.9!
It also works on all Minecraft versions starting with 1.8.9
Please note that this Minecraft server software is currently not official and it's in an alpha state, the current version is v.0.0.1 and please also note that this server software currently only works on the Minecraft: Java Edition. 
If you only have the Minecraft: Pocket Edition on your mobile device or the Bedrock Edition on your PC and/or your console, see this here: https://github.com/Atten007/RaspMCPE or install a plugin (e.g. GeyserMC).
At least 2GB RAM is required or RaspMC won't work! To start this server, simply double click the file "main.py", use the shell script or type in the following code in your terminal:
<code>git clone https://github.com/Atten007/RaspMC.git</code>
<code>cd RaspMC</code>
<code>python3 main.py</code>
Have fun playing Minecraft with your new Minecraft: Java Edition server on your Raspberry Pi!

# Requirements
- 2GB RAM or more (1GB will also work but with random crashes etc.)
- At least Python 3.11
- At least Minecraft 1.8.9 (Support for older versions will come later!)
- A 64-Bit CPU with a 64-Bit Operating System (32-Bit CPUs and/or Operating Systems aren't currently supported due to the less amount of RAM <1GB)

# Updates
## v.0.0.1 (??.05.2022)

- Initial release
- Two default worldgen-options: Superflat and default (can be adjusted in the config at the section world-type)
- Procedurally generated worlds
- support for up to ??? players
- very simple structures and features (e.g. villages, shipwrecks, pillager outposts, mineshafts and dungeons)
- supports all Minecraft: Java Edition versions starting 1.19
- plug-in and mod support. Mods should also be installed on the client and plugins should be written with Python 3.11 or newer. Java Plugins won't work!

# FAQ

Coming soon

# Compatibility

Coming soon
