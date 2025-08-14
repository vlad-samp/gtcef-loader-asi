# ASI Script for loading GTCEF
This is a simple ASI script just to load an external dll. So i don't have to go through the process of making a proper way to load all the files in the game. *Maybe one day i'll have to..*

# Why ASI ?
Why not ? It's pointless to reinvent the wheel. 

ASI scripts are basically just DLLs with `.asi` extension instead of `.dll`.
If you're interested in creating advanced ASI scripts just go [there](https://github.com/DK22Pac/plugin-sdk), that is SDK provided by plenty of good modders from the community.

But if you're still wondering why i use an ASI loader, i just don't want to use DLL injection or hijacking, it could prevent players from installing some mods and that's not the point. This CEF should be working with any mods.

# Compile
This project is developped under Windows with [mingw](https://www.mingw-w64.org/) C++ compiler tools and [Make](https://gnuwin32.sourceforge.net/packages/make.htm).
*If you want to change the compiler, you have to edit that [file](https://github.com/vlad-samp/gtcef-loader-asi/blob/main/Makefile).*

Simply go in the root directory and type:
`make -k`
The output file should be in the same directory.
