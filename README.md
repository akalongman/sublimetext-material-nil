Sublime Text 2/3 Material Nil Theme
------------------------------------------------------------------------


Material Nil is the dark theme for the Sublime Text 2/3.


This theme is based on [Nil Theme](https://github.com/nilium/st2-nil-theme) and
[Material Theme](https://github.com/equinusocio/material-theme)


Options
------------------------------------------------------------------------

There are a handful of options you can use to customize the appearance
of both the Nil and Ayin themes. All options are boolean values and
disabled by default. Their keys and descriptions follow:

* `material_nil_highlight_modified_tabs` — If true, will display an orange bar under
  tabs with modified buffers.
* `material_nil_sidebar_folders` — If true, will display a folder icon beside folders
  in the sidebar instead of a disclosure triangle. Sidebar folders are
  off by default.
* `material_nil_colored_folder_glyphs` — If true, will tint either folder icons or
  disclosure triangles in the sidebar (only the sidebar) purple.
* `material_nil_disable_colored_group_labels` — If true, will disable the colored
  group labels. Group labels are the things that say "Group 1" and 2 and
  so on in the sidebar. They're only visible if you have open files
  shown. Colored group labels are enabled by default.
* `material_nil_disable_colored_folder_labels` — If true, will disable the colored
  folder labels in the sidebar. This is independent of group label
  coloring. Colored folder labels are enabled by default.
* `material_nil_disable_fileicons` — If true, will disable the colored
  folder labels in the sidebar. This is independent of group label
  coloring. Colored folder labels are enabled by default.


To set any of these properties, place them and their values in your user
preferences file.


HDPI Displays
------------------------------------------------------------------------

This theme includes HDPI images for displays that support HDPI on Mac
OS X, such as the recent (as of this writing) MacBook Pro with the
retina display.  Both screenshots above are in HDPI.


## Installation

**With the Package Control plugin:** The easiest way to install Material Nil is through Package Control, which can be found at this site: https://sublime.wbond.net/installation

Once you install Package Control, restart Sublime Text and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows). Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select Material Nil when the list appears. The advantage of using this method is that Package Control will automatically keep Material Nil up to date with the latest version.

**Without Git:** Download the latest source from [GitHub](https://github.com/akalongman/sublimetext-material-nil) and copy the Material Nil folder to your Sublime Text "Packages" directory.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/akalongman/sublimetext-material-nil.git Material Nil


The "Packages" directory is located at:

* OS X:

        ST2: ~/Library/Application Support/Sublime Text 2/Packages/
        ST3: ~/Library/Application Support/Sublime Text 3/Packages/

* Linux:

        ST2: ~/.config/sublime-text-2/Packages/
        ST3: ~/.config/sublime-text-3/Packages/

* Windows:

        ST2: %APPDATA%/Sublime Text 2/Packages/
        ST3: %APPDATA%/Sublime Text 3/Packages/


Activating
------------------------------------------------------------------------

In your `Settings - User` file, set the
`"theme"` key to `"Material-Nil.sublime-theme"`, like
so:

    {
        "theme": "Material-Nil.sublime-theme"
    }

Assuming you have then installed it correctly, it should show the theme.
Due to what I assume is settings from previous themes surviving, you may
wish to restart Sublime Text as well, but otherwise you should be good
to go.
