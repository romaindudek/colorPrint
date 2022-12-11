# colorPrint
colorPrint is a very light weight module that enables tou to print in color without having to use fstring codes and memorising complicated ...

I wrote it in order to save time when I'm coding scripts that generates a lot of terminal prompts which are painfull to read wthout colors !

## Basic usage
The script uses a cprint function and tags in the string starting by the `§` symbol.

```python
from colorPrint import cprint

# First Try :
cprint("Now I can use §-SUCCESSGreen color !")

cprint("The §_INFOtext§ I want to §_SUCCESSprint§ using §_WARNINGWarning background!")

# Same with shortcodes :
cprint("The §_#Itext§ I want to §_#Sprint§ using §_#WBackground colors!")
cprint("Or §-#Itext§ using §-#WForeground colors!")

# compatibility
cprint("colorPrint is §-#Icompatible§ with the usage of the § §§_#Scharacter§ if you need it §-#Danyway§ !")
```

![ScreenShot ColorPrint Module](https://github.com/romaindudek/colorPrint/blob/medias/ScreenShot_colorprint.png?raw=true)

As simple as that !