KickAss.sublime-build
=====================

Custom build system for Sublime Text 2 and KickAssembler (6502)


# Options

### cmd

    "cmd": ["$file_path/build.sh"],

`build.sh` is a custom script I wrote to compile my project (`51 Pegasus`). 
So be sure to change the build.sh script to match what you're trying to do.

    "selector": "source.assembly.6502.kickassembler",

I've associated `*.asm` files with `Sublime Text 2` and I have created
a custom bundle to work with Sublime Text 2 and Kick Assembler.

This can be found here:  https://github.com/cbmeeks/cbmeeks-6502kickass-asm-tmbundle

If you need to find the selector, press `ALT+COMMAND+p` on the Mac.

    "shell": true

This tells Sublime Text 2 to use the shell (bash) and echo the output back in the editor.

If you have any questions, drop me a line!  `cbmeeks [at] gmail [dot] com`
