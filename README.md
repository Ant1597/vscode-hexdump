# vscode-hexdump

[![GitHub issues](https://img.shields.io/github/issues/stef-levesque/vscode-hexdump.svg)](https://github.com/stef-levesque/vscode-hexdump/issues)
[![GitHub license button](https://img.shields.io/github/license/stef-levesque/vscode-hexdump.svg)](https://github.com/stef-levesque/vscode-hexdump/blob/master/LICENSE.md)
[![VS Code marketplace button](http://vsmarketplacebadge.apphb.com/installs/slevesque.vscode-hexdump.svg)](https://marketplace.visualstudio.com/items?itemName=slevesque.vscode-hexdump)
[![Gitter chat button](https://img.shields.io/gitter/room/stef-levesque/vscode-hexdump.svg)](https://gitter.im/stef-levesque/vscode-hexdump)

hexdump for Visual Studio Code

## Description

Display a specified file in hexadecimal

## Main Features

Right-click on a file in the explorer to see *Show Hexdump*  
![Show hexdump](images/show-hexdump.png)

Hover in the data section to see numerical values  
![Hover DataView](images/hover-dataview.png)

Right-click in the hexdump to see more options  
![Context Menu](images/context-menu.png)

*Show Hexdump* icon
![Title Icon](images/title-icon.png)

## Commands

* `hexdumpFile` (`ctrl+shift+alt+h`, `cmd+shift+alt+h`) Show Hexdump
* `editValue` (`shift+enter`) Edit Value Under Cursor
* `gotoAddress` (`ctrl+g`) Go to Address...
* `exportToFile` (`ctrl+s`, `cmd+s`) Export to Binary File...

## Configuration

* `hexdump.littleEndian` Set default endianness (true for little endian, false for big endian)
* `hexdump.nibbles` How many nibbles per group (2, 4)
* `hexdump.uppercase` Display hex digits in uppercase
* `hexdump.width` Number of bytes per line (8, 16, 32)
* `hexdump.showOffset` Show offset on first line
* `hexdump.showAddress` Show address on each line
* `hexdump.showAscii` Show ASCII section

## Installation

1. Install *Visual Studio Code* (1.7.0 or higher)
2. Launch *Code*
3. From the command palette `ctrl+shift+p` (Windows, Linux) or `cmd+shift+p` (OS X)
4. Select `Install Extension`
5. Choose the extension `hexdump for VSCode`
6. Reload *Visual Studio Code*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Requirements

Visual Studio Code v1.7.0

## Credits

* [Visual Studio Code](https://code.visualstudio.com/)
* [vscode-docs on GitHub](https://github.com/Microsoft/vscode-docs)
* [hexdump-nodejs on GitHub](https://github.com/bma73/hexdump-nodejs)
* [hexy.js on GitHub](https://github.com/a2800276/hexy.js)

## License

[MIT](LICENSE.md)
