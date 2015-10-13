# Faarikaal Theme

### WORK IN PROGRESS!
**This theme is *not* yet submitted to package control, even though this file contains installation instructions and other information suggesting it is.**

<!-- monochromatic, -->

A minimalistic, flat and dark theme for Sublime Text 3 that aims to put focus on your code and to make other elements less intrusive.

Faarikaal is based upon the brilliant [Soda Theme](https://github.com/buymeasoda/soda-theme) by [Ian Hill](http://buymeasoda.com/), with inspiration from Gravity, El Capitan, Haft Lang, Devastate and Spacegray (and the Atom theme One Dark)...

This theme uses icons from the great [Font Awesome](http://fortawesome.github.io/Font-Awesome/)

<!-- Project site: [http://eivind88.github.io/faarikaal/](http://eivind88.github.io/faarikaal/ -->

## Design

![Faarikaal Theme](faarikaal.png?)

## Installation

Faarikaal theme is designed to work with the latest beta builds of [Sublime Text 3](http://www.sublimetext.com/3).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Soda Theme via the `Package Control: Install Package` menu item. The Soda Theme package is listed as `Theme - Faarikaal` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/eivind88/faarikaal/ "Theme - Faarikaal"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `faarikaal`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Faarikaal.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Faarikaal.sublime-theme"
    }

<!--
## Additional Features

### Sidebar Folder Icons

Faarikaal has folder icons by default with Sublime Text.

![Soda Folder Icons](http://buymeasoda.github.com/soda-theme/images/features/sidebar-folder-icons.png)

### Retina Resolution UI

Faarikaal has been designed to take advantage of retina resolution (high-dpi) displays.

![Soda Retina](http://buymeasoda.github.com/soda-theme/images/features/soda-retina.png)

## Bonus Options

-->

### Syntax Highlighting Colour Schemes

The colors scheme shown in the screenshot is a modified version of Tomorrow Night Bright,
which is distributed with the Faarikaal theme.

This color scheme can be enabled by adding (or updating) your color scheme entry to be `"color_scheme": "CustomTomorrowNightBright.tmTheme"`

**Example Sublime Text 3 User Settings**

    {
        "color_scheme": "CustomTomorrowNightBright.tmTheme"
    }

### Code Font

The code font shown in the screenshot is [Source Code Pro](https://github.com/adobe-fonts/source-code-pro).

## License

Faarikaal is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Faarikaal Theme by Eivind Arvesen (http://www.eivindarvesen.com)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Faarikaal Theme" (or a close variant) in the main project title, repo name or Package Control name.
