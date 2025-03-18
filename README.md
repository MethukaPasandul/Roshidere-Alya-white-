# Roshidere Alya (White) - Browser Theme

A browser theme inspiring Alisa Mikhailovna, a popular roshidere anime charcter. I made this theme specialy for her fans.

![Theme Preview - background](theme_ntp_background.png)

## Installation
Via [Chrome Store](https://chromewebstore.google.com/detail/roshidere-alyawhite/mbgggdmlcllmckdbagbgdldeinanllcj)

## Making Changes
If u like to customize the theme further,
- Make changes in manifest.json file to change colors or any other properties.(explained below)
- Replace theme_ntp_background.png with your own image if u like to change the background image

## Understanding manifest.json
This mini guide will help you to understand what each property using for in manifest.json file what each do.

### Basic Properties to understand
- manifest_version: the version of manifest file format. version 3 for chrome themes
- version: The version of your theme (ex:- 1.0.0)
- name: The name of your theme
```
{
  "manifest_version": 3,
  "version": "1.0.0",
  "name": "Roshidere Alya(white)",
.
.
.
}
```
### Theme Properties
theme object contains visual configuration of this theme, like colours and background wallpeper.
#### Background
theme_ntp_background stands for background image for the NTP(New Tab Page) Add path of image.
#### Colors
colors defines the color scheme for various parts of the browser UI. Each color is specified in RGB format

- frame: The color of the browser frame (the top part of the window).
```
"frame": [229,171,197],
```

- ntp_background: The background color of the New Tab Page.
```
"ntp_background": [111,204,188],
```

- tab_text: The color of the text in active tabs.
```
"tab_text": [161,50,78],
```

- tab_background_text: The color of the text in inactive tabs.
```
"tab_background_text": [161,50,78],
```

- bookmark_text: The color of the text in the bookmarks bar.
```
"bookmark_text": [181,71,118],
```

- ntp_text: The color of the text on the New Tab Page.
```
"ntp_text": [181,71,118],
```

- ntp_link: The color of links on the New Tab Page.
```
"ntp_link": [6,55,116],
```

- ntp_header: The color of headers on the New Tab Page.
```
"ntp_header": [156,156,156],
```

- toolbar: The background color of the toolbar.
```
"toolbar": [170,221,227],
```

- toolbar_text: The color of the text in the toolbar.
```
"toolbar_text": [187,122,150],
```

- button_background: The background color of buttons
```
"button_background": [0,0,0,0],
```

- toolbar_button_icon: The color of icons in the toolbar.
```
"toolbar_button_icon": [187,122,150],
```

- omnibox_background: The background color of the address bar.
```
"omnibox_background": [230,252,255]
```

- buttons: Specifies the tint for buttons. The array [0, 0, 1] applies a default tint.
```
"tints": {
      "buttons": [0,0,1]
    },
```

#### Properties
- ntp_background_alignment stands for the alignment of the background image on the New Tab Page(NTP)
- ntp_background_repeat tells whether the background image repeat or not
```
"properties": {
      "ntp_background_alignment": "center top",
      "ntp_background_repeat": "no-repeat"
    }
```

## Screenshots
Heres how it looks like after installation on browser
![sample](/Screenshots/ss1.png)

## Credit for image
by [Doga Kobo](https://wall.alphacoders.com/big.php?i=1371400)