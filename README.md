# Solarized Light & Dark Theme for Xcode: Fira Code Edition
#### - Enjoy the world's most-popular theme for programming on Xcode, now with lovely ligatures
![Solarized Light][1]
![Solarized Dark][2]

## Solarized?
[Solarized][3] is a theme which uses the same text colors for both light and dark backgrounds for consistency. You can see the overall effect in the screenshots above.

## Fira Code?
[Fira Code][4] is a typeface which produces helpful ligatures (e.g. `!=` becomes `≠`, `->` becomes `⟶`, `>=` becomes `⩾`, etc.) when reading your code. The effect isn't particularly noticable in the screenshots above; see the [Fira Code GitHub page][4] for better examples.

## Installation
> *Tested working on Xcode 10*

1. Download and install the [Fira Code][4] typeface.
2. Copy the two .xccolortheme files into `~/Library/Developer/Xcode/UserData/FontAndColorThemes`. You may have to create the directory if there isn't an existed one.
3. Open `Preferences`. In the `Fonts & Colors` tab, select `Solarized Light` or `Dark` theme. If they don't appear, restart Xcode and check again. _(Note: From macOS Mojave (10.14) forward, your chosen theme is bound to the systemwide light/dark modes. For example, if you change the system to light mode and select Solarized Light in Xcode, then change to dark mode and choose Solarized Dark, Xcode will remember your theme selections any time you change the system between light/dark modes.)_

## Attributions
Solarized, Fira Code, the themes upon which those in this project are based, and the code in the screenshots are not my work! I imported two separate themes, tweaked them for Xcode 10, added in Fira Code, and forked another project. Credit is due there!

## See also
- [Solarized Theme official homepage][3]
- [Fira Coda typeface][4]
- [Solarized Light & Dark Theme For Xcode][5] (forked from here)
- [Solarized Light for Xcode][6] (based on this theme)
- [Solarized Dark for Xcode][7] (based on this theme)
- [Swift: 30 Projects][8] (code in screenshots)

[1]: https://github.com/CartoonChess/solarized-xcode-with-fira-code/blob/master/Screenshot_Light.png
[2]: https://github.com/CartoonChess/solarized-xcode-with-fira-code/blob/master/Screenshot_Dark.png
[3]: http://ethanschoonover.com/solarized
[4]: https://github.com/tonsky/FiraCode
[5]: https://github.com/stackia/solarized-xcode
[6]: https://github.com/nelsyeung/Solarized-Light-for-Xcode
[7]: https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode
[8]: https://github.com/soapyigu/Swift-30-Projects
