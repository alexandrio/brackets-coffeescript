# Brackets CoffeeScript
An extension for [Brackets](https://github.com/adobe/brackets) that improves [CoffeeScript](https://github.com/jashkenas/coffeescript) syntax highlighting.

It is meant as a temporary solution to use while waiting for an improved [CodeMirror](https://github.com/codemirror/CodeMirror) mode.

It uses the same coloring conventions as the JavaScript mode.

Improved syntax highlighting comes at the cost of some advanced features of the official mode.

![Sample](http://i.imgur.com/goPBJdx.png)

## Installation
The extension isn't listed in the [Brackets Extension Registry](https://brackets-registry.aboutweb.com/) yet, thus requiring manual installation.

1. Clone or download the repository.
2. In Brackets, `Help > Show Extensions Folder`.
3. Paste the repository in the `user` folder.
4. In Brackets, `Debug > Reload With Extensions` or `F5`

## Known Issues
* All variables assignments are recognized as definitions.
* No help is provided with indentation.
