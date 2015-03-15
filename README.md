# Notepad++ plugins for Touhou Danmakufu ph3
##Description
Set of Notepad++ plugins for Touhou Danmakufu ph3 (東方弾幕風) scripting language. Includes auto completion config and syntax highlighting configs.
##Features
- Syntax highlighting for Danmakufu ph3 scripts (.dnh)
- Default and Bespin color themes
- Code completion for ph3 engine library functions and constants 
- Calltip function documentation

![Alt text](/screenshot/dmf-auto.png?raw=true "Autocomplete")
![Alt text](/screenshot/dmf-doc.png?raw=true "Calltip")
![Alt text](/screenshot/dmf-default.png?raw=true "Default theme")
![Alt text](/screenshot/dmf-bespin.png?raw=true "Bespin theme")

##Installation
To install auto completion config copy Danmakufu.ph3.xml to your Nodepad++ installation directory \plugins\APIs.
To enable auto completion go to Settings → Preferences... → Auto-Completion and select "Function completion" or "Function and word completion". For calltips check "Function parameters hint on input".

To install syntax highlighting go to Language → Define your language..., press Import... button and select the xml file.

For default theme use dmf.default.xml, and for Bespin theme use dmf.bespin.xml.

##Known limitations
- Windows-1252 encoding used for calltip documentation. Not sure but this seems to be Notepad++ limitation (utf-8 config doesn't work).
- Autocomplete window doesn't appear when a calltip is shown. Notepad++ limitation.
- Calltips only work for function and not for constants. Scintilla limitation.
- Cannot change calltip background or text color. Scintilla limitation.