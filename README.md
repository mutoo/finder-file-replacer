finder-file-replacer
====================

a simple utility to replace files by select src_file and dest_file from Finder via workflow services.

Install
-------

1. Right click on "copy_path_from_finder.workflow" > Open > Install;
2. Same to "replace_file_with_clipboard.workflow";
3. open "Apple > System Preferences > Keyboard > Shortcuts > Services";
4. find "copy_path_from_finder" and add shortcut to it, (e.g. Ctrl+Shift+C);
5. find "replace_file_with_clipboard" and add shortcut to it, (e.g. Ctrl+Shift+V);

Usage
-----

1. Select the **source file** from finder;
2. Press the shortcut for "copy_path_from_finder";
3. Select the **destination file** your want to override from finder;
4. Press the shortcur fot "replace_file_with_clipboard";
5. Repeat from 3 for more files to override;

**Notices** These two Services only work for single file;

TODO
----

* Prevents multiple-file-selection;