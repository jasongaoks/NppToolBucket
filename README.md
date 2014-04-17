NppToolBucket
=============

A plugin for Notepad++ written in C# .NET Framework 2.0.

Features
--------

ToolBucket contains the following features:

* Multi-line search and replace dialog
* Change indentation dialog
* Generate GUID
* Generate Lorem Ipsum
* Compute MD5 Hash
* Compute SHA1 Hash
* Base 64 encode
* Base 64 decode

Download
--------

Release versions can be downloaded from [phdesign.com.au](http://www.phdesign.com.au/npptoolbucket)

Installation
------------

Copy the NppToolBucket.dll file to your Notepad++\plugins directory.

Dependencies
------------

Requires .NET Framework 2.0 or higher to be installed on the system.

Version history
---------------

### v1.5
* Keyboard shortcut Alt+Shift+G to generate GUIDs
* An interface for options to generate GUIDs
* A bugfix for the indentation settings dialog where settings are applied even if cancelled

### v1.4
* Implemented Ctrl-A in textboxes to select all text
* Fixed bug when closing search and replace that active window doesn't return to notepad++
* Increase search / replace history length in dropdown to 60 characters and removed line breaks

### v1.3
* Implemented replace all in all open documents

### v1.2
* Initial release
