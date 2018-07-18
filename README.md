# Seti

[![Packagecontrol total downloads](https://img.shields.io/packagecontrol/dt/Seti_UI.svg)](https://packagecontrol.io/packages/Seti_UI/)

`SublimeText 3 Theme` Port of Seti_UI by [jesseweed](https://github.com/jesseweed/seti-ui)

### Seti

![Seti Screenshot](./Resource/screenshot-1.png)

### Seti_orig

![Seti Screenshot](./Resource/screenshot-2.png)

## Notes

* [Seti_UX](https://sublime.wbond.net/packages/Seti_UX) A New/Better syntax Highlight.
* [Seti_JetBrains](https://github.com/zchee/Seti_JetBrains) by [zchee](https://github.com/zchee) :tophat:.

## Install

Theme is listed as [Seti_UI](https://packagecontrol.io/packages/Seti_UI) on Will Bond's [Sublime Package Control](https://packagecontrol.io).

## Setup

Activate the `Theme` by calling `UI: Select Theme` from Sublime Text quick menu.

#### Options

open your Sublime Text "user settings" and add what you need from below.
* note that not all the settings are available in both themes.

```js
// tabs
  "Seti_tabs_small"                   // tabs height = 35
  "Seti_tabs_med"                     // tabs height = 40
  "Seti_tabs_big"                     // tabs height = "seti=45" / "seti_orig=54"
  "Seti_tabs_no_min_width"            // (issues/223)
  "Seti_tab_font_12"                  // tab font size = 12
  "mouse_wheel_tabswitch"             // scroll through opened tabs
  "Seti_no_scroll_icons"              // remove the l/r arrows, effective when ("enable_tab_scrolling": true)
  "Seti_no_under_bar"                 // remove the small colored bar under the un-saved tabs "not available with accents"
  "Seti_bold_slctdtab_labels"         // make active tab label font in bold
  "Seti_use_system_title_bar"         // use the new tabset feature (>=3127)

// tabs unsaved bar ("Seti_accent_*": false)
  "Seti_yellow_tab"
  "Seti_red_tab"
  "Seti_indigo_tab"
  "Seti_purple_tab"
  "Seti_teal_tab"
  "Seti_lime_tab"
  "Seti_seablue_tab"

// tab close button ("Seti_accent": false)
  "Seti_yellow_tabclose"
  "Seti_red_tabclose"
  "Seti_indigo_tabclose"
  "Seti_purple_tabclose"
  "Seti_teal_tabclose"
  "Seti_lime_tabclose"

// tab label
  "Seti_blue_label"
  "Seti_yellow_label"
  "Seti_red_label"
  "Seti_indigo_label"
  "Seti_purple_label"
  "Seti_teal_label"
  "Seti_lime_label"

// scrollbar
  "Seti_SB_med"                    // scrollbars width / height = 6
  "Seti_SB_big"                    // scrollbars width / height = 10
  "Seti_blue_scrollbar"
  "Seti_yellow_scrollbar"
  "Seti_red_scrollbar"
  "Seti_indigo_scrollbar"
  "Seti_purple_scrollbar"
  "Seti_teal_scrollbar"
  "Seti_lime_scrollbar"
  "Seti_seablue_scrollbar"

// sidebar
  // icons
  "Seti_ClosedFolder_same"         // same icon as the "Opened folder"
  "Seti_ClosedFolder_remove"       // remove closed_folder icon
  "Seti_ClosedFolder_dots"         // change closed_folder icon to dot
  "Seti_ClosedFolder_anim"         // animate sidebar folder icons
  "Seti_sb_no_icons"               // (issues/133)
  "Seti_sb_blank"                  // (issues/133)
  // padding
  "Seti_sb_small_padding"          // sidebar entries padding = 3
  "Seti_sb_big_padding"            // sidebar entries padding = 10
  "Seti_sb_tree_med"               // sidebar tree padding = 15
  "Seti_sb_tree_small"             // sidebar tree padding = 10
  "Seti_sb_tree_tiny"              // (issues/88)
  "Seti_sb_tree_miny"              // (issues/88)
  "Seti_show_group_arrows"         // show the folder/group arrows in sidebar
  // labels
  "Seti_bold_slctdfile_labels"     // make the sidebar selected file text in bold
  "Seti_sidebar_font_size_12"      // (issues/115)
  "Seti_sidebar_font_size_13"      // (issues/115)
  "Seti_sidebar_font_size_14"      // (issues/115)
  "Seti_sidebar_font_Ubuntu"       // (issues/115)
  "Seti_sidebar_font_Fira"         // (issues/115)
  "Seti_sidebar_font_Hack"         // (issues/115)
  "Seti_sidebar_font_Source"       // (issues/115)
  "Seti_heading_font_12"           // heading font size = 12
  // heading
  "Seti_bold_heading"              // make heading font in bold
  "Seti_no_heading"                // remove the "folder,group 1,etc.."
  "Seti_top_heading_big"           // sidebar top header img big
  "Seti_top_heading_small"         // sidebar top header img small
  "Seti_top_heading_anim"          // sidebar top header img animate on hover "not available with accents"
  "Seti_alt_tree_row"              // alternative sidebar row highlight

// view
  "Seti_pad_5"                     // use with line_padding_bottom / line_padding_top = 5
  "Seti_pad_3"                     // use with line_padding_bottom / line_padding_top = 3
  "Seti_panel_nrml"                // remove the padding top/down from quick panel
  "Seti_dark_fold_button"          // change the fold arrow to black

// map
  "Seti_yellow_map"
  "Seti_red_map"
  "Seti_indigo_map"
  "Seti_purple_map"
  "Seti_teal_map"
  "Seti_lime_map"
  "Seti_seablue_map"

// status bar
  "Seti_yellow_statusbar"
  "Seti_red_statusbar"
  "Seti_indigo_statusbar"
  "Seti_purple_statusbar"
  "Seti_teal_statusbar"
  "Seti_lime_statusbar"
  "Seti_seablue_statusbar"

// accents
  "Seti_accent"                    // general options for accents
  "Seti_accent_yellow"
  "Seti_accent_red"
  "Seti_accent_indigo"
  "Seti_accent_purple"
  "Seti_accent_teal"
  "Seti_accent_lime"
  "Seti_accent_seablue"
```

## Differences from the original

* No file icon in the opened tabs, ST lacks this.
* Current line number highlight color, ST lacks this.
