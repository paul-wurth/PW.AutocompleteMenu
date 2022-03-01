# PW.AutocompleteMenu

A customizable autocomplete menu for WinForms `RichTextBox`, `TextBox` and other controls.  
It allows you to easily embed drop-down hints into any `TextBox` control on your form.

Forked from [this project](https://www.codeproject.com/Articles/365974/Autocomplete-Menu) by Pavel Torgashov to add support for .NET Core/5+.

![AutocompleteMenu Sample](https://www.codeproject.com/KB/menus/365974/AutocompleteMenu.png)
![AutocompleteMenu Animated sample](https://www.codeproject.com/KB/menus/365974/am.gif)

Supported platforms:
- .NET Core 3.1 and .NET 5+
- .NET Framework 2.x, 3.x and 4.x

## Features

It supports advanced scenarios like custom autocomplete menu with keywords, snippets, method suggestions, text correctors, etc. Menu items can be dynamically context-sensitive, depending on the text.  
One can also customize the menu UI with multiple columns, hosted `ListView`, etc.  
Autocomplete menu is compatible with any text editor control (derived from `TextBoxBase` or by creating your own wrapper class that implements the `ITextBoxWrapper` interface).

More details: https://www.codeproject.com/Articles/365974/Autocomplete-Menu

## License

Copyright © Pavel Torgashov, 2012-2015, pavel_torgashov@ukr.net.  
Copyright © Paul Wurth S.A. 2022.

This repository is licensed with the [GNU Lesser General Public License v3.0 only (LGPL-3.0-only)](/COPYING.LESSER). See also the [GNU General Public License v3.0 only (GPL-3.0-only)](/COPYING).
