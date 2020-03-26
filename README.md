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


Installation
============

Simple install procedure:

  1. run the 'configure' script
  - **meson . build**
  2. build xed
  - **ninja -v -C build**
  3. install xed *Become root if necessary*
  - **ninja install -v  -C  build**

SCREEN-SHOTS
![test-screenshot](/screencaptures/xed-screenshot-1.png?raw=true)

> xed is released under the GNU General Public License (GPL) version 2, see
> the file 'COPYING' for more information.
