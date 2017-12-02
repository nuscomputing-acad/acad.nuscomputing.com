---
title: "Vim Commands"
description: ""
featured_image: ''
---

Note: All commands are case sensitive.

|Useful Vim Commands| |
|---|---|
|i|Switch to insert mode.
Programs can only be edited when you are in Insert Mode.|
|ESC|Switch to Command Mode|
|gg=G|Indent all parts of the code.|
|v|Start visual mode per character. To highlight certain parts of the code.|
|y|Yank (copy) text.|
|yy or Y|Yank (copy) one line.|
|{count}yy|Yank (copy) {count} lines.|
|d|Delete (cut) text.|
|dd|Delete (cut) one line.|
|{count}dd|Delete (cut) {count} lines.|
|p|Put (Paste) the text after the cursor.|
|u|Undo last change.|
|CTRL+R|Redo last change which was undone.|
|{count}G|Goto line {count} in the file, on the first non-blank character.|
|:w|Write (save) the current file.|
|:wq|Write (save) the current file and quit VIM.|
|:q|Quit VIM.|
|:q!|Quit VIM without writing (saving)|
|TAB|Autocomplete file name.

> Example: Accessing vim Testing123456.java. You can type “vim Te” and press TAB to complete the filename.

|File Commands| |
|---|---|
|cp|to CoPy files|
|mv|to MoVe files from one directory to another; can also be used to rename files.|
|rm|to ReMove files. Be careful with this command — files deleted cannot be restored (unless they have been backed up during the normal backup cycle).|

|Commands to display text files| |
|---|---|
|cat|to string together or display (CATenate) the contents of files onto the screen|
|less|variant of “cat” (includes features to read each page leisurely)|

|Directory Commands||
|---|---|
|pwd|to Print current Working Directory to show you which directory you are currently in.|
|ls|to LiSt files in your current directory You may also use “ls -F” for more information (-F is one of the many options/flags available for the ls command. To see a complete list of the options, refer to the man pages, ie. “man ls“.) The slash (/) beside the filename tells you that the file is a directory (folder). A normal file does not have a slash (/) beside its name when “ls -F” is used. You may also use the “ls -l” command (hyphen el, not hyphen one) to display almost all the file information, include the size of the file and the date of modification. Try it now!|
|cd|to Change Directory from current directory to another. To use this command, type cd \<another directory>, where \<another directory> has to be specified by the user. Note that the prompt changes to ~/c to indicate that you are now in the c directory below your HOME directory. Entering “cd” alone brings you back to your HOME directory, ie. the directory in which you started with when you first logged into the system.|
|mkdir|to MaKe a subDIRectory in current directory|
|rmdir|to ReMove a subDIRectory in current directory — note that a directory must be empty before it can be removed.|