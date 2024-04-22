[screenshot]:       https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/template1.png
[light]:            https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/template1.png
[dark]:             https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/template1.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/Saltssaumure/template-discord-theme/Template.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/template-discord-theme/net.saltssaumure.Template.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/Saltssaumure/template-discord-theme?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/Saltssaumure/template-discord-theme
[issues]:           https://github.com/Saltssaumure/template-discord-theme/issues
[license]:          https://github.com/Saltssaumure/template-discord-theme/blob/main/LICENSE
[.theme.css]:       https://github.com/Saltssaumure/template-discord-theme/blob/main/Template.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Template "Replugged store page"
[release-bd-gh]:    https://github.com/Saltssaumure/template-discord-theme/releases/latest/download/Template.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/Saltssaumure/template-discord-theme/releases/latest/download/net.saltssaumure.Template.asar "Get latest release"

# Template Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A template Discord theme for multiple client mod support.***

![Screenshot of Template applied to Discord][screenshot]

| Light mode                                                     | Dark mode                                                    |
| -------------------------------------------------------------- | ------------------------------------------------------------ |
| ![Screenshot of Template light mode applied to Discord][light] | ![Screenshot of Template dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `Template.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Replugged][Replugged]
#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Template.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `Template.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltssaumure.github.io/template-discord-theme/Template.theme.css`

## Customisation

| Description                    | Variable name     | Valid values                    | Default value |
| ------------------------------ | ----------------- | ------------------------------- | ------------- |
| Background colour              | `--temp-bg-color` | Any [colour][css-color].        | #000          |
| &#9936; Moving scanline on/off | `--temp-scanline` | `block` (on) or `none` (off).   | `block`       |
| &#9888; Screen flicker on/off  | `--temp-flicker`  | `flicker` (on) or `none` (off). | `none`        |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-20 of [`Template.theme.css`][.theme.css].
3. Edit the variable values and save.

### Vencord
#### Local
2. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
3. Open `Template.theme.css` with your favourite text editor.
4. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`Template.theme.css`][.theme.css].
3. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].