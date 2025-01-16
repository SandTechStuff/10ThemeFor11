# 10ThemeFor11

> [!NOTE]  
> This theme is about 50% complete. To track its progress, check the ["Theme Progress"](https://github.com/SandTechStuff/10ThemeFor11/issues/1) issue.
> When most assets are completed, a proper theme will be provided in releases.

10ThemeFor11 is an `.msstyles` theme for Windows 11 that aims to provide accurate Windows 10 controls, to the greatest extent that Windows 11 allows.

# Installation

First, you need to install a UxTheme patcher to allow custom `.msstyles` themes since Microsoft locks them out by default. Some options include the Windhawk mod [UXTheme hook](https://windhawk.net/mods/uxtheme-hook) and [SecureUxTheme](https://github.com/namazso/SecureUxTheme).

_This theme has only been tested using the UXTheme hook Windhawk mod._

1. After patching UxTheme, download the latest release of the theme from [Releases](https://github.com/SandTechStuff/10ThemeFor11/releases) (10ThemeFor11.zip).
2. Extract the downloaded zip and place the contents in `C:\Windows\Resources\Themes`.

_The file structure should resemble this._

- `C:`
	- `Windows`
		- `Resources`
			- `Themes`
				- `10ThemeFor11`
				- `10ThemeFor11_Dark.theme`
				- `10ThemeFor11_Light.theme`
3. Either double click one of the `.theme` files from within the `Themes` folder or select your desired theme from within Windows settings.
4. The theme comes bundled with the Windows 10 wallpaper and accent color, but if you would prefer to use your own wallpapers or colors you can override anything through Windows personalization settings.

### Recommendations

I recommend using the _Disable Rounded Corners on Windows 11_ Windhawk mod. As most Windows 10 controls have sharp corners, having rounded windows can look strange.

### Why not use the stock Windows 10 `aero.msstyles` file?

While the stock Windows 10 `.msstyles` theme works on Windows 11, it is only partially compatible. For example, the context menus and animations are broken. 10ThemeFor11 uses the assets from the stock Windows 10 `.msstyles` but reformats them in the way Windows 11 expects.
