# Seti

`SublimeText 3 Theme & ColorScheme` Port of Seti_UI & Syntax by [jesseweed](https://github.com/jesseweed/seti-ui)

![Seti Screenshot](screenshot-1.jpg)
![Seti Screenshot](screenshot-2.jpg)


# Notes
- This is my first of its kind so if you found any bugs ,please issue a ticket.

- The Theme is considered in beta- <strike>phase till the TODO list is done</strike> ish.

- I included a folder with some files types from `jesseweed` and `DanBrooker` to test the icons ,you should probably add some of them to the "file_exclude_patterns" as ST wont open them anyway.

- any thing less than 'ST3 Build 3062' wont get the sidebar icons to work.


## Install

### Via Package Control

Theme is listed as `Seti_ST3` in Will Bond's [Sublime Package Control](https://sublime.wbond.net).

### Manual

1. [Download the .zip](https://github.com/ctf0/Seti_ST3/archive/master.zip).
2. Unzip and rename the folder to ```Seti_ST3```.
3. Copy the folder into `Packages` directory, which you can find using the menu item `Preferences -> Browse Packages...` in Sublime Text.
4. copy the (fold.png) "or edit it to ur liking" to ```Packages/User/Theme - Default``` to override the _focken default yellow icon.

## Setup

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Preferences -> Settings - User` in Sublime Text or get `Schemr` & `Themr` by [Ben Weier](https://github.com/benweier).

### Example settings
```
{
  "theme": "Seti.sublime-theme",
  "color_scheme": "Packages/Theme - Seti/Seti.tmTheme",
  "caret_extra_width": 2 // to have a wider/thicker caret
}
```

### Credits

- Theme is Originally by [jesseweed](https://github.com/jesseweed/seti-ui).

- Ported based on `Glacier` by [joeyfigaro](https://github.com/joeyfigaro/glacier-theme) among many others.

- Special thanx for [Anthony Garand](https://github.com/garand) for the widget files (took me 2 days to understand what they actually do O_o and fix the god dame text input thing).

- `ScopeHunter` by [facelessuser](https://github.com/facelessuser) "YOU ROCK".

- `ColorSchemeEditor` by [Borislav Peev](https://github.com/bobef) "HOF".

- `Neon` by [Matt Morrison](https://github.com/MattDMo/Neon-color-scheme) "HOF".


### Differences from the original

- No file icon in the opened tabs, ST lacks this.

- Not as icon rich as the original because ST can't see anything other than Extensions ,and even thou its still hard to make it use the icon you want "thats why some icons are duplicated".

- Some scopes have different colors in Atom like the (:) ,this is related to the tmLanguage file in ST. <strike>(i included an Atom version of the same ColorScheme i made for sublime , install it and test it with the included JS file to see the difference)</strike> ,also note that Atom sometimes will display a different color than ST "even if the scope was the same" ,some scopes color like (heading in MD files) was changed to make it easir to read.

- Current line number color, ST lacks this.

- Everything else is basically the same as the original except for a couple of UI colors.


### TODO

1. Make the search input field shorter or "slimier" (depend on which side of the earth you are living).
2. <strike>Find a solution for the million file icons which ST lacks out of the box ,or at least get the recognized ones to display their correct icons as expected.</strike> Done For The Most Part.
3. <strike>Clean up the "icon_?.tmPreferences" files so they actually do something.</strike> Done For The Most Part.
4. haven't tested on Retina ,so anyone with Retina Mac plz test and report any found bugs.

<strike>5. Edit the color scheme to have different color for the same scope depends on file ext (js,html,css) ,some scops already have this ability but am looking to extend it even further.</strike>