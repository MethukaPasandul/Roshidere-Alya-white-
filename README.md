# Roshidere Alya (White) - Browser Theme

A beautiful and elegant browser theme inspired by **Alisa Mikhailovna**, a famous anime character from the series *"Roshidere"*. This theme features a soft, pastel color palette and a stunning background image of Alisa, creating a serene and visually appealing browsing experience.

![Theme Preview](theme_ntp_background.png)


## Features
- **Custom Background**: A high-quality wallpaper featuring Alisa Mikhailovna.
- **Pastel Color Scheme**: A soothing combination of pinks, blues, and whites.
- **Optimized for Chrome**: Designed to work seamlessly with Chrome's New Tab Page (NTP).


## Installation
Via [Chrome Webstore](https://chromewebstore.google.com/detail/roshidere-alyawhite/mbgggdmlcllmckdbagbgdldeinanllcj).


## Customization
If you'd like to customize the theme further,
- Edit the manifest.json file to change colors or other properties.
- Replace theme_ntp_background.png with your own image (recommended size: 1920x1080).

## Guide to manifest.json
This mini guide will help you to understand what each property will do in manifest.json file.
The theme object contains the visual configuration for your theme.

### Basic Properties
- manifest_version: Specifies the version of the manifest file format. For Chrome themes, this should be 3.
```
"manifest_version": 3,
```
- version: The version of your theme (e.g., 1.0.0).
```
  "version": "1.0.0",
```
- name: The name of your theme (e.g., Roshidere Alya (White)).
```
"name": "Roshidere Alya(white)",
```
### Theme Properties
The theme object contains the visual configuration for your theme.
#### Background image
theme_ntp_background: Specifies the background image for the New Tab Page (NTP). This should be the path to your image file (e.g., theme_ntp_background.png).
#### Colors
The colors object defines the color scheme for various parts of the browser UI. Each color is specified as an RGB array (e.g., [229, 171, 197]).

- frame: The color of the browser frame (the top part of the window).
```
"frame": [
        229,
        171,
        197
      ],
```

- ntp_background: The background color of the New Tab Page.
```
"ntp_background": [
        111,
        204,
        188
      ],
```

- tab_text: The color of the text in active tabs.
```
"tab_text": [
        161,
        50,
        78
      ],
```

- tab_background_text: The color of the text in inactive tabs.
```
"tab_background_text": [
        161,
        50,
        78
      ],
```

- bookmark_text: The color of the text in the bookmarks bar.
```
"bookmark_text": [
        181,
        71,
        118
      ],
```

- ntp_text: The color of the text on the New Tab Page.
```
"ntp_text": [
        181,
        71,
        118
      ],
```

- ntp_link: The color of links on the New Tab Page.
```
"ntp_link": [
        6,
        55,
        116
      ],
```

- ntp_header: The color of headers on the New Tab Page.
```
"ntp_header": [
        156,
        156,
        156
      ],
```

- toolbar: The background color of the toolbar.
```
"toolbar": [
        170,
        221,
        227
      ],
```

- toolbar_text: The color of the text in the toolbar.
```
"toolbar_text": [
        187,
        122,
        150
      ],
```

- button_background: The background color of buttons
```
"button_background": [
        0,
        0,
        0,
        0
      ],
```

- toolbar_button_icon: The color of icons in the toolbar.
```
"toolbar_button_icon": [
        187,
        122,
        150
      ],
```

- omnibox_background: The background color of the address bar.
```
"omnibox_background": [
        230,
        252,
        255
      ]
```

- buttons: Specifies the tint for buttons. The array [0, 0, 1] applies a default tint.
```
"tints": {
      "buttons": [
        0,
        0,
        1
      ]
    },
```

#### Properties
- ntp_background_alignment: Specifies the alignment of the background image on the New Tab Page
- ntp_background_repeat: Specifies whether the background image should repeat
```
"properties": {
      "ntp_background_alignment": "center top",
      "ntp_background_repeat": "no-repeat"
    }
```

## Screenshots
Heres how it looks like after installation on browser
![sample](/Screenshots/ss1.png)