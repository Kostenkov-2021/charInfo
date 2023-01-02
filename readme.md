# Character information

* Author: Cyrille Bougot
* NVDA compatibility: 2022.3.3 and beyond
* Download [stable version][1]
* Download [development version][2]

This add-on allows to present in a message various information about a character.

## Presented information

The presented information include the following sections:

* Unicode: information from Unicode norm, i.e. name, CLDR name, value, block, etc.
* MS font, only for characters written with proprietary Microsoft fonts (Symbol, Wingding 1, 2, 3 and Webding): name and information about the equivalent Unicode character.
* NVDA symbol description: information allowing to understand how NVDA reports the symbol description. NVDA uses the information in the top most rows containing available information to provide the description of a symbol.
* NVDA character description: information allowing to understand how NVDA reports the character description (e.g. "alpha" for "A"). NVDA uses the information in the top most rows containing available information to provide the description of a character.


## Commands

* Numpad2 (all keyboard layouts) or NVDA+. (laptop layout): when pressed 4 times, displays information about the character of the current navigator object where the review cursor is situated.
* Unassigned: Presents a message with detailed information on the character of the current navigator object where the review cursor is situated. If you feel uncomfortable with the four press gesture, you may assign to it a gesture in NVDA's input gesture dialog ("Text review" category).
* Unassigned: Presents a message with detailed information on the character at the position of the caret (works only in places where there is a caret). It can be found in the "system caret" category of NVDA input gestures dialog.

## Notes

* Two commands are unassigned by default. They need to be assigned in the Input gestures dialog to be used.
* The provided information in the Unicode section is in English since it is part of Unicode norm. If a local translation exists for this add-on, the information is also provided alongside with English.


## Change log

### Version 1.9

* On Windows lock screen, the script to review the current character can now operate normally (single, double or triple press).
* Drops compatibility with NVDA below 2022.3.3. The last version compatible with NVDA 2019.3 is the [1.8][downloadVersion1.8].

### Version 1.8

* Update to Unicode 14.0.
* Compatibility with NVDA 2022.1.
* Drops compatibility with NVDA below 2019.3. The last version compatible with NVDA 2017.3 is the [1.7][downloadVersion1.7].
* The release is now performed thanks to a GitHub action instead of appVeyor.
* Update localizations.

### Version 1.7

* Added localizations.

### Version 1.6

* Compatibility NVDA 2021.1.

### Version 1.5

* Prepare compatibility with NVDA 2021.1 (contribution Łukasz Golonka).
* Update along with last modifications on add-on template.

### Version 1.4

* Added a script to get information for the character at the caret position (contribution Łukasz Golonka).
* Update to Unicode 13.0.

### Version 1.3

* Fixes a bug with NVDA 2019.3.


### Version 1.2

* Provides additional information on characters written with Microsoft fonts.


### Version 1.1

* Updates to support newer versions of NVDA (Python 2 and 3 compatible)
* Releases performed now with appveyor


### Version 1.0

* Initial release.

[1]: https://addons.nvda-project.org/files/get.php?file=chari

[2]: https://addons.nvda-project.org/files/get.php?file=chari-dev

[downloadVersion1.7]: https://github.com/CyrilleB79/charInfo/releases/download/V1.7/charInfo-1.7.nvda-addon

[downloadVersion1.8]: https://github.com/CyrilleB79/charInfo/releases/download/V1.8/charInfo-1.8.nvda-addon
