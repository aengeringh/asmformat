# Assembly Formatter

NOTICE: The author NotAFlyingGoose does no longer maintain the AsmFormat repo. This is a fork to implement features I need personally. Changes:

* Ignore text inside double quotes (avoid adding whitespace around / path separators)
* Apart from .asm files, also format .inc files


Assembly Formatter will format your .asm files!
Just right click on a .asm file and select `Format Asm`, or press `ctrl-shift-p` then type `Format Asm` and press Enter.

![Assembly Formatter at use](https://i.imgur.com/INc2uh3.png)

This is extension is a vscode port of https://www.lartu.net/projects/asmformat/

Full credits go to the nice people over there.

To build the .vsix extension file:

```shell
npx @vscode/vsce package
```