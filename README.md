# Faarikaal Theme

<!-- monochromatic, -->

A minimalistic, flat and dark theme for Sublime Text 3 that aims to put focus on your code and to make other elements less intrusive.

Faarikaal is based upon [Soda Theme](https://github.com/buymeasoda/soda-theme) by [Ian Hill](http://buymeasoda.com/), and is partially inspired by other Sublime Text themes like [Gravity](https://github.com/frankyonnetti/gravity-sublime-theme), [El Capitan](https://github.com/iccir/El-Capitan-Theme), [Devastate](https://github.com/vlakarados/devastate) and [Spacegray](https://github.com/kkga/spacegray), in addition to the Atom theme [One Dark](https://github.com/atom/one-dark-ui).

This theme uses icons from [Font Awesome](http://fortawesome.github.io/Font-Awesome/).

<!-- Project site: [http://eivind88.github.io/faarikaal/](http://eivind88.github.io/faarikaal/ -->

## Design

![Faarikaal Theme](faarikaal.png?)

## Installation

Faarikaal theme is designed to work with the latest beta builds of [Sublime Text 3](http://www.sublimetext.com/3).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Soda Theme via the `Package Control: Install Package` menu item. The Faarikaal Theme package is listed as `Theme - Faarikaal` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area, and regularly pulling from upstream.

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

The color scheme shown in the screenshot is a modified version of [Tomorrow](https://github.com/ChrisKempson/Tomorrow-Theme) Night Bright (based on the file from [this](https://github.com/theymaybecoders/sublime-tomorrow-theme) repo), which is distributed with the Faarikaal theme.

This color scheme can be enabled by adding (or updating) your color scheme entry to be `"color_scheme": "CustomTomorrowNightBright.tmTheme"`

**Example Sublime Text 3 User Settings**

    {
        "color_scheme": "CustomTomorrowNightBright.tmTheme"
    }

### Code Font

The code font shown in the screenshot is [Source Code Pro](https://github.com/adobe-fonts/source-code-pro).

## License

Faarikaal is licensed under the [MIT License](LICENSE.txt).
