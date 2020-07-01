# ecl-editors
_Compilation of the various (known) ECL Colourisers and Editors_

## Scintilla
_Scintilla is an open source c++ cross platform editor_

* Home:  https://www.scintilla.org/    
* Project:  https://sourceforge.net/projects/scintilla/
* ECL Definition:  https://sourceforge.net/p/scintilla/code/ci/default/tree/lexers/LexECL.cxx
* Also used in:
    * SciTE
    * Notepad++

## ECL IDE
_Windows ECL IDE reuses the Scintilla editor, with a custom version of LexECL_
* Project:  https://github.com/hpcc-systems/eclide
* ECL Definition:  https://github.com/hpcc-systems/eclide/blob/master/EclEditor/LexECL.cxx

## VS Code - ECL Language Extension
_ECL Support for VSCode - based on TextMate definitions_

* Home:  https://marketplace.visualstudio.com/items?itemName=hpcc-systems.ecl
* Project:  https://github.com/hpcc-systems/vscode-ecl
* ECL Definition:  https://github.com/hpcc-systems/vscode-ecl/blob/master/syntaxes/ecl.tmLanguage.json

## CodeMirror
_Web based (JavaScript) editor_

* Home:  https://codemirror.net/
* Project:  https://github.com/codemirror/codemirror
* ECL Definition:  https://github.com/codemirror/CodeMirror/blob/master/mode/ecl/ecl.js

## Pygments
_Python based syntax highlighter_

* Home:  https://pygments.org/
* Project:  https://github.com/pygments/pygments
* ECL Definition:  https://github.com/pygments/pygments/blob/master/pygments/lexers/ecl.py

## Rouge
_Rouge is a pure Ruby syntax highlighter_

* Project:  https://github.com/rouge-ruby/rouge
* ECL Definition:  https://github.com/rouge-ruby/rouge/blob/master/lib/rouge/lexers/ecl.rb

## Eclipse IDE (deprecated)
_Eclipse IDE (Java)_

* Home: https://www.eclipse.org/ide/
* ECL Definition:  https://github.com/hpcc-systems/EclipsePlugin

## Future...
_Future frameworks that could be supported???_

* Monaco
* Ace
* TextMate (the VS Code extension above may "just work")
* pygmentize.js
* Highlight.js
