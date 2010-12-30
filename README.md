# Phing support for TextMate

This TMBundle provides Phing support for TextMate. Here are some of the things you can do with this bundle:

* Run Phing from within TextMate (there are even some special targets to speed your development).
* Generate a new `build.xml` file.
* Use tab-completed snippets to quickly add new targets, tasks, filesets, etc.
* With full syntax support, TextMate can help you quickly navigate from target to target.

## Installation

1. Clone this repository or download a snapshot.
2. Put Phing.tmbundle in `~/Library/Application\ Support/TextMate/Bundles/` (You can symlink if you want).
3. Restart TextMate

## Usage



* Create a new Phing `build.xml` using `File » New From Template  » Phing » build.xml`.
* Turn on Phing-specific syntax highlighting for a build XML file by choosing `Phing` from the language selection menu.
* Create a new target by typing `target` and then hitting tab.
* Run a target within TextMate by typing ⌘-U
* See the `Bundles » Phing` menu for more.

### Project-centered

The Phing bundle is designed to work inside of a TextMate project. By default, it attempts to find the `build.xml` file within the root of a project.

Not all features will work when (1) a `build.xml` file cannot be found or (2) TextMate is editing a single file, not a project.

## About

This bundle was written by Matt Butcher. The official repository is [at GitHub](https://github.com/technosophos/Phing-TMBundle).

This project is released under an MIT-style license.

## License

Phing-TMBundle | 
Matt Butcher matt at aleph-null dt tv | 
Copyright (C) 2010 Matt Butcher

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.