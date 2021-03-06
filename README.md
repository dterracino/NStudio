# NStudio

NStudio is a free (open source) editor that was written in C# on the .NET 2.0 Framework.
The idea of NStudio is to support all the features of one perfect text editor.
NStudio has 5 modules for editing text (Scintilla, Rich Text Editor, ICSharpCode editor, Standart windows editor and WYSIWYG HTML Editor), web browser, plugins and many tools.

* http://www.softpedia.com/get/Office-tools/Text-editors/NStudio.shtml
* http://www.download.bg/index.php?cls=program&mtd=default&id=431379
* http://fileforum.betanews.com/detail/NStudio/1179220914/1
* http://softvisia.com/download.php?view.1033

## Features
Here are some key features of "NStudio":
- 5 editing components (Scintilla editor, ICSharpCode editor, HTML WYSIWYG editor, Rich text editor and Standart Windows editor)
- Syntax Highlighting
- Multi-Document
- Web and File Browser
- Very good and beauty user interface (support Office2007 style)
- Highly configurable and customizable.
- Plugins
- Multi-language (English, Bulgarian, Hungarian, Latvian, Russian)
- Drag and Drop support
- Source code printing
- Brace and Indent guideline Highlighting
- Clipboard ring, Math tools, System Information tool, Directory Watcher and Console

## Screenshot

![NStudio Screenshot](http://www.download.bg/upl/progs/sc2.6410.PNG)

## Changelog
####0.1-beta3 (0030) (16-09-2007)
- Added: Added Hungarian language (translated by Sasa)
- Updated: FileSearch plugin version 4.1.3 (a lot of bug fixes and some changes)
- Updated: ICSharpCode.TextEditor updated to version 2.2.1.2678
- Updated: WeifenLuo.WinFormsUI.Docking updated to 2.1 revision 40 from SVN
- Updated: ICSharpCode.SharpZipLib.dll updated to 0.85.4.369
- Changed: No more assembly signing

####0.1-beta2 (0020) (03-08-2007)
- Added: A lot of code optimizations made
- Added: Update button in about menu
- Updated: ICSharpCode.TextEditor updated to version 2.2.1.2622
- Fixed: Menu is still up after clicking item
- Fixed: Save all is now working
- Fixed: Saving is now available for documents not only in the document section
- Fixed: Some shortcuts key added/fixed
- Installer: Added missing file "ICSharpCode.SharpZipLib.dll" for CodeSnippet plugin

####0.1-beta1 (0010) (16-07-2007)
- Feature: Added installer for the program
- Feature: Added version checker (at program statup)
- Added: CodeSnippet plugin v0.1
- Added: WindowsMediaPlayer plugin v0.1
- Added: Added Russian language (translated by Moth)
- Added: Added Latvian language (translated by Moth)
- Changed: Some changes in About form
- Changed: Sites for program changed (new: http://nstudio.nrpg.info, http://nrpg.info)
- Fixed: Assembly information for all assemblies fixed
- Updated: ICSharpCode.TextEditor updated to version 2.2.0.2595 (Final 2.2)

####0.1-alpha9 (0009) (24-06-2007)
- Feature: Added new editor: HTML WYSIWYG Editor
- Feature: Added print and print preview functions for most of text editors
- Feature: Scintilla menu changed (supports renderer styles)
- Feature: On document open in Scintilla, program automatically loads language specifications for the file
- Updated: Scintilla component updated to version 1.74
- Updated: ICSharpCode.TextEditor updated to version 2.2.0.2579
- Added: Some shortcut keys for the menu commands
- Added: New editing function: 'reverse text'
- Changed: Removed open links for all editors. Now when user select file for open he can select editor from dialog box.
- Fixed: Text editing functions are now working for ICSharpCode editor
- Fixed: Smart identing is now enabled for Scintilla text editor component
- Fixed: Status bar text for tools and editors

####0.1-alpha8 (0008) (09-06-2007)
- Feature: Added new tool: ConZole 0.1 (Command Prompt clone)
- Feature: Added new tool: System Information 0.1 (Some system information)
- Feature: Added new tool: Directory Watcher 0.1 (Spy your directories)
- Updated: ICSharpCode.TextEditor updated to version 2.2.0.2541
- Fixed: When close document the program always ask for save
- Fixed: Bug with loading 'rtf' files
- Fixed: Now all assemblies (without NStudio.exe) have valid strong names
- Fixed: All FxCop suggesions fixed for Bulgarian.dll
- Fixed: All FxCop suggesions fixed for NStudioResources.dll
- Fixed: Some FxCop suggesions fixed for all other assemblies

####0.1-alpha7 (0007) (30-05-2007)
- Feature: Added ability to scan 'Plugins folder' for plugins
- Feature: Added 4 text case edit options
- Added: Context menu to ICSharpCode Editor
- Added: Context menu to Tray Icon
- Added: Info in the status bar about current tab or content
- Updated: FileSearch plugin version 0.21 (Can open multiple tabs, Menu is now context for each tab)
- Updated: Browser v0.31 (now uses program status bar instead of his own)
- Updated: WeifenLuo.WinFormsUI.Docking updated to version 2.1
- Updated: ICSharpCode.TextEditor updated to version 2.1.0.2527
- Fixed: All edit functions in ICSharpCode Editor are now working correctly
- Fixed: Plugin Manager optimized
- Fixed: Now it is not possible to load one plugin multiple times
- Fixed: Added scroll bar to Standard Editor
- Fixed: Bug with text delete
- Fixed: Few GUI bugs fixed

####0.1-alpha6 (0006) (27-05-2007)
- Feature: Added multi-language GUI system (English language is default)
- Feature: Added new type of text editor(light and fast): Windows Standart Text Editor (like Notepad)
- Added: Added Bulgarian language
- Added: File menu improved (added closing functions)
- Updated: ICSharpCode.TextEditor updated to version 2.1.0.2526
- Updated: Math Tools v0.2 (added expressions evaluator)
- Fixed: Options dialog is no more showing in task bar
- Fixed: Few GUI bugs fixed

####0.1-alpha5 (0005) (24-05-2007)
- Feature: Added tray icon. Users can select to minimize program to tray.
- Feature: Added new tool: Clipboard ring v0.1 (Enhanced clipboard manager)
- Feature: Added new tool: Math tools v0.1 (Converts numbers between a variety of number bases)
- Added: Few settings added (show toolbars and status bar)
- Updated: Browser v0.3 (status bar improvements, new window handing, some optimizations, bugs fixed)
- Changed: Some changes in about form
- Changed: Few GUI improvements in About form
- Fixed: All functions in Rich Text Editor are now working correctly
- Fixed: Fixed bug with check status of some menu and toolbars items
- Fixed: Fixed bug with opacity (always is 1.0)

####0.1-alpha4 (0004) (21-05-2007)
- Feature: Users can select the opacity of program from 'view' menu
- Feature: Users can select to show/hide status bar
- Feature: Users can select to enable/disable Top Most function of the program
- Added: Program forum link added to 'about menu'
- Added: Few settings added (show toolbars and status bar)
- Updated: Integrated Browser component updated to version 0.2 (GUI imrovements, Page text added to tab text)
- Updated: ICSharpCode.TextEditor updated to version 2.1.0.2520
- Updated: Scintilla.NET component updated (compiled latest source code with code optimizations and without debug information)
- Changed: Program resources are now in separate '.dll' file 
- Changed: Moving toolbars under the status bar is now available
- Changed: Program icon changed

####0.1-alpha3 (0003) (16-05-2007)
- Feature: Added drag and drop support for files in program
- Feature: Added basic options dialog
- Feature: The program can save/load some settings from 'config.xml'
- Feature: The program save last form possition, size, window state, and some settings
- Feature: The program load last loaded plugins at startup
- Added: About form with info for NStudio
- Added: Some items in 'About menu'
- Updated: FileSearch plugin updated to version 0.2 (Fixed some bugs, fixed column headers text)
- Updated: ICSharpCode.TextEditor updated to version 2.1.0.2519
- Fixed: The initial directory for plugin browser fixed

####0.1-alpha2 (0002) (14-05-2007)
- Feature: Added renderer support (System, Professional and Office 2007 style)
- Feature: Added visual style support (User can select the visual style)
- Feature: Users can select to show/hide some of the toolbars from 'View menu'
- Added: FileSearch plugin v0.1
- Added: Program icon
- Added: Menu items for renderer and visual style in 'View menu'
- Added: Menu items in file menu (New, Open, Save, Save all, Print, Print preview)
- Added: Menu items in edit menu (Undo, Redo, Cut, Copy, Paste, Delete, Select all)
- Updated: ICSharpCode.TextEditor updated to version 2.1.0.2518
- Fixed: Renderer tool bar items fixed.
- Fixed: Fixed some bugs where active content is not treated as a document

####0.1-alpha1 (0001) (12-05-2007)
- First Release
