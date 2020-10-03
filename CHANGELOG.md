# Change Log

## 0.7.0 (FORK)
- Switched to lowercase in almost every piece of code and remove some spaces (this is a very personal change)
- Added get_buffer_string and get_buffer_char functions
- Added timeline_create function snnipet
- Added PARSE code block snnipet with SNAPI functions for messages with this format: HEADER-Param,Value

## 0.6.1
- Changed AXI file to Netlinx Source
- Changed aliases of languages to AMX Netlinx Source and AMX Netlinx Library

## 0.6.0
- Added document format provider

## 0.5.4
- Fixed beautifier finding false positives inside string literals

## 0.5.3
- More code beautifier tweaking

### 0.5.2
- Updated Netlinx grammar with most recent Netlinx.AXI constants and function names
- Updated grammar types to get better theme integration support
- Added .LIB file extension support

### 0.5.1
- Updated Netlinx grammar for compiler directives and keywords (jwjames83)
- Snippet updates (sentry07)

### 0.5.0
- Added a second build task for compiling with local files only, ignoring the global folders.
- Removed context shortcut and keyboard shortcut to compile the current file. Please use the Build tasks noted above.
- Complete rewrite of the beautifier indentation code. Should be much more reliable now.

### 0.4.3
- Debugging the new indentation logic

### 0.4.2
- Rewrote code indentation logic in the code beautifier

### 0.4.1
- Fixed build task showing up in other filetypes. Only shows up in .AXS file windows now.
- Fixed excess terminal windows when opening helpfile/diagnostics/file transfer

### 0.4.0
- Fixed build task generation - Use CTRL+SHIFT+B to build your source files!
- Fixed problem matcher for newer NLRC.exe version output

### 0.3.3
- Context menu organization
- More snippets for storage types
- Default editor config overrides

### 0.3.2
- Bug fixes in syntax highlighting

### 0.3.0
- Converted extension to TypeScript
- Added Build command. Can use the previous shortcut or use CTRL+SHIFT+B and select the build task.
- Added workspace configuration defaults for the extension to work better with snippets.

### 0.2.1
- Removing double quoted strings as a string container. It prevented autocomplete and other things to function inside strings.
- Fixed "FOR" code snippet

### 0.2.0
- More Code Snippets
- Published to Extension Marketplace

### 0.1.2
- Added base Netlinx code snippets

### 0.1.1
- Beta release
