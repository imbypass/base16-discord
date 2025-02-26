# base16-discord
A lightweight recoloring of the default [Discord](https://discord.com/) theme to use [base16](https://github.com/tinted-theming/schemes/tree/spec-0.11/base16) color schemes.


### Installation (QuickCSS Import):
1. Install a client mod for Discord, such as [Vencord](https://vencord.dev/) or [Legcord](https://legcord.app/).
2. Paste the following snippet into your client mod's QuickCSS:
```css
@import url('https://imbypass.pw/base16-discord');
```


### Installation (Local):
1. Install a client mod for Discord, such as [Vencord](https://vencord.dev/) or [Legcord](https://legcord.app/).
2. Download the [base16-discord](https://github.com/imbypass/base16-discord) theme for your client mod.
3. Place the downloaded theme to your client mod's theme directory. (e.g., `~/.config/Vencord/themes/base16-discord`)
4. Refresh your theme list (if applicable) and enable the theme in your settings.

### Customizing:
`base16-discord` exposes a few variables to make it super easy to match your system theme.
You can use modify these variables inside your QuickCSS to customize the theme's colors and fonts.
*(QuickCSS changes are live-reloaded so you can see the changes instantly.)*
```css
:root {
    --font: "ZedMono Nerd Font Propo";
    --font-code: "ZedMono Nerd Font Propo";

    --base00: #121212;
    --base01: #181818;
    --base02: #303030;
    --base03: #505050;
    --base04: #B0B0B0;
    --base05: #DCDFE0;
    --base06: #E0E0E0;
    --base07: #F5F5F5;
    --base08: #E27373;
    --base09: #FFBA7B;
    --base0A: #F9CF7A;
    --base0B: #94B979;
    --base0C: #00988E;
    --base0D: #97BEDC;
    --base0E: #E1C0FA;
    --base0F: #D4ACA7;
}
```

## Preview:
![base16-discord (Tokyo Night)](https://0x0.st/8AgE.png)
