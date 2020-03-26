# Linux Mint Xed

xed is a small and lightweight text editor.

xed supports most standard editing features, plus several not found in your
average text editor (plugins being the most notable of these).

Although new features are always under development, currently xed has:

    * Complete support for UTF-8 text
    * Syntax highlighting
    * Support for editing remote files
    * Search and Replace
    * Printing and Print Previewing Support
    * File Revert
    * A complete preferences interface
    * Configurable Plugin system, with optional python support

Some of the plugins, packaged and installed with xed include, among others:

    * Word count
    * Spell checker
    * Change case of selected text
    * File Browser
    * Sort
    * Insert Date/Time
    * Tag list


## Installation

  1. run the 'configure' script
  - **meson . build**
  2. build xed
  - **ninja -v -C build**
  3. install xed *Become root if necessary*
  - **ninja install -v  -C  build**

### Xed look and feel

##### Classic Mode
![classic-screenshot](/screencaptures/classic_screencapture.png?raw=true)

##### Theme selections
![theme-screenshot](/screencaptures/theme_screencapture.png?raw=true)

##### Search and Replace feature
![search-replace-screenshot](/screencaptures/search_replace_screencapture.png?raw=true)

##### Select from several languages in Highlight syntax mode
![highlightmode-screenshot](/screencaptures/highlightmode_screencapture.png?raw=true)

##### Xed Shortcuts
![shortcuts-1-screenshot](/screencaptures/shortcuts_1_screencapture.png?raw=true)
![shortcuts-2-screenshot](/screencaptures/shortcuts_2_screencapture.png?raw=true)



> xed is released under the GNU General Public License (GPL) version 2, see
> the file 'COPYING' for more information.
