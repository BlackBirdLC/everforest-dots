# Everforest dotfiles

## Overview

These are my dotfiles as of January 26, 2025. I will update this repository when new versions of the themes included are released to reflect my own setup (for as long as I continue to use it). 

Included are themes and configurations for GNOME, text editor, GTK, cursors, icons, Ghostty, Micro, Firefox, several shell extensions, and links to more.

## How to Install

Drop the contents of the included folders into to the corresponding .-variants on your system (config to .config). Be sure to check before overwriting any files; you probably want to change or append your configuration files rather than overwriting them.

### Shell Extensions

Install the the shell extensions listed below. Some serve a similar purpose, but I was only satisfied when combining them all. Feel free to experiment and mix and match. Load the included configuration files for Open Bar and Tiling Shell, and set the border color to `#7ab2ab` in Rounded Window Corners Reborn. Again, these are my settings; feel free to pick a different accent color that better matches your taste.

#### Required:
- [AppIndicator and KStatusNotifierItem Support](https://github.com/ubuntu/gnome-shell-extension-appindicator)
- [Dash to Dock](https://github.com/micheleg/dash-to-dock)
- [Open Bar](https://github.com/neuromorph/openbar)
- [Rounded Window Corners Reborn](https://github.com/flexagoon/rounded-window-corners)
- [Tiling Shell](https://github.com/domferr/tilingshell)
- [Useless Gaps](https://github.com/mipmip/gnome-shell-extensions-useless-gaps)
- [User Themes](https://gitlab.gnome.org/GNOME/gnome-shell-extensions)

#### Optional but Recommended:
- [Battery Time](https://github.com/pomoke/battery_time)
- [Disconnect Wifi](https://github.com/kgshank/gse-disconnect-wifi)
- [Media Controls](https://github.com/sakithb/media-controls)
- [Vitals](https://github.com/corecoding/Vitals)

#### Other extensions I use:
- [Color Picker](https://github.com/tuberry/color-picker)
- [Custom Command Toggle](https://github.com/StorageB/custom-command-toggle)
- [GPU Supergfxctl Switch](https://github.com/chikobara/GPU-Switcher-Supergfxctl)
- [NordVPN Quick Toggle](https://github.com/Wedaxi/NordVPN-Quick-Toggle)

### Other Themes

#### GNOME Text Editor

Copy the everforest theme found in `.local/share/gedit/styles` to `/usr/share/gnome-text-editor/styles`.

#### Visual Studio Code

Install [sainnhe](https://github.com/sainnhe)'s [Everforest color scheme for VSCode](https://github.com/sainnhe/everforest-vscode) from the Marketplace.

#### Firefox

Install one of the many themes available. I personally use [Minimalist Everforest](https://addons.mozilla.org/en-US/firefox/addon/minimalist-everforest) by [canbeardig](https://addons.mozilla.org/en-US/firefox/user/15578079) as it highlights the active tab.

I like to add the following CSS to my `userChrome.css` to adjust the spacing of the window buttons:

```
.titlebar-buttonbox-container .titlebar-buttonbox {
    margin-right:+10px !important;
}
```

There is also a theme for [Thunderbird](https://addons.thunderbird.net/en-US/thunderbird/addon/everforest).

#### Telegram

Install the theme from this link: [Telegram Theme](https://t.me/addtheme/Z29CUAVsrr87MUN3) (unknown author).

## How to Use

Once all themes are installed, you should be able to find them inside your applications like GNOME Tweaks, as well as in all the other applications you installed themes for.

## Notes

The screenshots can show some inconsistent theming and configurations. I planned to upload this back in late January or early February, but I've been too occupied with other things. After reviewing the color accent settings, I have a feeling that multiple unrelated UI elements became a different color, but that might just be my imagination.

Later this year, I will be switching away from GNOME as my daily driver. I will then update this repository with the latest versions of the included themes and archive it.

## Credits

 - [sainnhe](https://github.com/sainnhe) for creating the color scheme.
 - [Fausto-Korpsvart](https://github.com/Fausto-Korpsvart) for creating the Everforest Shell, GTK, and icon themes.
 
