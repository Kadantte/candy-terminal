# Candy - a Windows Terminal theme

![alt text][logo]

[logo]: https://raw.githubusercontent.com/Kadantte/candy-terminal/master/assets/candy.png "Candy - a Windows Terminal theme"

## Installation

1. In Windows Terminal, press `Ctrl+Shift+,` (or open **Settings** and click **Open JSON file**). Your `settings.json` opens. Note the folder it is in.

2. Make a copy of your `settings.json`, in case you want to revert the changes.

3. Copy `candy.small.png` and `candy.large.png` from the `candy` folder in this repository into that same folder.

4. Merge [`candy/settings.json`](candy/settings.json) into your own `settings.json`:
   - add everything inside its `profiles.defaults` to your `profiles.defaults`
   - add the `Candy` entry to your `schemes` list

   Don't replace your whole `settings.json` with this one, or you lose your own profiles and key bindings.

Using a portable (unpackaged) Windows Terminal? `ms-appdata:///local/` doesn't work there, so set `backgroundImage` to the full path of the image instead.

## Fonts

The theme uses **Cascadia Code NF**, the Nerd Font version of Cascadia Code (it has the extra icons many prompts use).

Download the latest `CascadiaCode-*.zip` from the [Cascadia Code releases](https://github.com/microsoft/cascadia-code/releases) and install the `CascadiaCodeNF` font files from its `ttf` folder.

## Image

There are two pictures: a large one, `candy.large.png`, and a small one, `candy.small.png`. The theme uses the small one. To use the large one, change `candy.small.png` to `candy.large.png` in `backgroundImage`.

## Acknowledgements

Image by [LeraPI](https://twitter.com/LeraPI_LP). The image is modified from the original (I just removed the background to make it transparent, nothing else), which can be found [here](https://twitter.com/LeraPI_LP/status/1404527030381776906). NSFW link!
