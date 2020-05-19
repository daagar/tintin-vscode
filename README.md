# tintin-vscode
A simple grammar for TinTin++ files in Visual Studio Code

Based on the TextMate/SublimeText version at https://github.com/tintinplusplus/tintinplusplus-sublimetext

I highly suggest using a bracket colorizer as well, such as https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2

## Installation

Install via:
```code --install-extension TinTinPlusPlus-<version>.vsix```

## Known Issues
There is no support for comment blocks like the following:
```
#nop {
    This should be commented out
};
```
The workaround is to instead multiselect lines to comment and use vscode's `ctrl+/` command to multicomment the lines. 


The following doesn't currently work right. Just split into two lines, this isn't an exercise in obfuscation! (or fix my horrid regex)
```
 #act {my trigger text} {#NOP comment here; #var notacomment real_code};
 ```



# TinTin++
Be sure to keep up with the latest TinTin++ updates at: https://tintin.mudhalla.net/index.php

Thanks to Scandum for an excellent client!

