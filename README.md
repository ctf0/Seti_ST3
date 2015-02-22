# Seti

`SublimeText 3 Theme & ColorScheme` Port of Seti_UI & Syntax by [jesseweed](https://github.com/jesseweed/seti-ui)

![Seti Screenshot](./+res/screenshot-1.png)


# Notes

- Any thing less than 'ST3 Build 3062' wont get the sidebar icons to work.

- if you used any of the resources in this repo into your own release ,plz appreciate the hard work and mention the original authors.

- A New/Better syntax Highlight released under [Seti_UX](https://sublime.wbond.net/packages/Seti_UX).

- [Seti_JetBrains](https://github.com/zchee/Seti_JetBrains) by [zchee](https://github.com/zchee) :tophat:.

## Install

### Via Package Control

Theme is listed as [Seti_UI](https://sublime.wbond.net/packages/Seti_UI) on Will Bond's [Sublime Package Control](https://sublime.wbond.net).

### Manual

1. [Download the .zip](https://github.com/ctf0/Seti_ST3/archive/master.zip).

2. Unzip and rename the folder to ``Seti_UI``.

3. Copy the folder into `Packages` directory, which you can find using the menu item `Preferences -> Browse Packages...` in Sublime Text.

4. copy the (+res/fold.png) "or edit it to ur liking" to ``Packages/Theme - Default`` to override the _focken default yellow icon.

## Setup

Activate the `Theme` and `Color-Scheme` by modifying your user preferences file, which you can find using the menu item `Preferences -> Settings - User` in Sublime Text or use `Schemr` & `Themr` by [Ben Weier](https://github.com/benweier).

### Example settings

```json
{
  "theme": "Seti.sublime-theme",
  "color_scheme": "Packages/Seti_UI/Scheme/Seti.tmTheme",
}
```

#### Options

`Themr` have an option call ``Themr: Toggle Theme Settings`` to change theme settings on-the-fly , or manually add what you need from below.

```
{
  "Seti_no_bar_undertabs": true,          // remove the 4px bar under the tabs
  "Seti_tabs_small": true,                // tabs height = 35
  "Seti_tabs_med": true,                  // tabs height = 40

  "Seti_ClosedFolder_same": true,         // same icon as the Opened_folder
  "Seti_ClosedFolder_remove": true,       // remove closed_folder icon
  "Seti_ClosedFolder_dots": true,         // change closed_folder icon to dot

  "Seti_SB_med": true,                    // scrollbars width / height = 6
  "Seti_SB_big": true,                    // scrollbars width / height = 10
  "Seti_SB_bright": true,                 // brighter color for scrollbars

  "Seti_sb_small_padding": true,          // sidebar entries padding = 3
  "Seti_sb_big_padding": true,            // sidebar entries padding = 10

  "Seti_sb_tree_med": true,               // sidebar tree padding = 15
  "Seti_sb_tree_small": true,             // sidebar tree padding = 10

  "Seti_sb_tree_tiny": true,              // check (issues/88)
  "Seti_sb_tree_miny": true,              // check (issues/88)

  "Seti_pad_5": true,                     // use with line_padding_bottom / line_padding_top = 5
  "Seti_pad_3": true,                     // use with line_padding_bottom / line_padding_top = 3

  "Seti_sb_wild": true,                   // experiment for sidebar
  "Seti_rainbow": true,                   // something different
  "Seti_in_4_a_treat": true,              // something crazy
}
```

## Credits

- Theme is Originally by [jesseweed](https://github.com/jesseweed/seti-ui).

- Ported based on `Glacier` by [joeyfigaro](https://github.com/joeyfigaro/glacier-theme) among many others.

- Special thanx for [Anthony Garand](https://github.com/garand) for the widget files (took me 2 days to understand what they actually do O_o and fix the god dame text input thing).

- `ScopeHunter` by [facelessuser](https://github.com/facelessuser) "YOU ROCK".

- `ColorSchemeEditor` by [Borislav Peev](https://github.com/bobef) "HOF".

- `Neon` by [Matt Morrison](https://github.com/MattDMo/Neon-color-scheme) "HOF".

- `Cyanide` by [lefoy](https://github.com/lefoy/cyanide-theme) "HOF".

## Differences from the original

- No file icon in the opened tabs, ST lacks this.

- <strike>Not as icon rich as the original because ST can't see anything other than Extensions ,and even thou its still hard to make it use the icon you want</strike>. ( A work around has been added on v7 )

- Some scopes have different colors in Atom like the `:` ,this is related to the tmLanguage file in ST ,also note that Atom sometimes will display a different color than ST "even if the scope name matches in both editors".

- Current line number highlight color, ST lacks this.

- Everything else is basically the same as the original except for a couple of UI colors.

## Issue A Ticket

1. what version of ST are you using ? (nothing lower than 3062).

2. have you restarted ST after you installed the theme ?.

3. if you still have bad render ,have you removed the cache folder ? (found right next to the packages folder).

4. have you copied the files from the "Ext" folder to your User folder ?.
