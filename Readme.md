# Rapid ST3 Setup  

![N|Solid](https://upload.wikimedia.org/wikipedia/en/thumb/d/d2/Sublime_Text_3_logo.png/150px-Sublime_Text_3_logo.png)

Repo's Main Moto to provide rapid **Sublime Text 3** Setup with awesome plugins and obviously with sleek theme.

**For Php, Css, Html, Javascript, json lint aka web-development. Please Download web-dev branch**

### Theme - [BOXY](https://packagecontrol.io/packages/Boxy%20Theme)

![N|Solid](https://packagecontrol.io/readmes/img/9b1d77c916844045f3c7f80cc4f39e4a47d94301.png)(https://packagecontrol.io/packages/Boxy%20Theme)

### Plugins

| Plugins        			| Discription   																										| More info on Installation  |
| ----------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------:| -------------------------------------------------------------:|
| All Autocomplete      		| Extend Sublime autocompletion to find matches in all open files of the current window 	| [Link](https://packagecontrol.io/packages/All%20Autocomplete) |
| GitGutter      			| A Sublime Text 2/3 plugin to see git diff in gutter 						| [Link](https://packagecontrol.io/packages/GitGutter)|
| SideBarEnhancements	| Enhancements to Sublime Text sidebar. Files and folders. 					| [Link](https://packagecontrol.io/packages/SideBarEnhancements)|
| SublimeLinter 		| Interactive code linting framework for Sublime Text 3 					| [Link](https://packagecontrol.io/packages/SublimeLinter)|
| SublimeLinter-csslint		| SublimeLinter plugin for CSS, using csslint. 							| [Link](https://packagecontrol.io/packages/SublimeLinter-csslint)|
| SublimeLinter-html-tidy	| SublimeLinter 3 plugin for html tidy. 								| [Link](https://packagecontrol.io/packages/SublimeLinter-html-tidy)|
| SublimeLinter-json		| SublimeLinter plugin for JSON. 								| [Link](https://packagecontrol.io/packages/SublimeLinter-json)|
| SublimeLinter-php		| SublimeLinter 3 plugin for PHP, using php -l. 							| [Link](https://packagecontrol.io/packages/SublimeLinter-phplint)|
| SublimeLinter-jshint		| SublimeLinter plugin for JavaScript, using jshint. 						| [Link](https://packagecontrol.io/packages/SublimeLinter-php)|


## Installation

 1. ``` CTRL/COMMAND + SHIFT + P ``` and Install ```Package Controller```
 2. Replace ALL repo files to ``` Browse Package Folder```.
 ![st3-browse-package](https://12621-presscdn-0-7-pagely.netdna-ssl.com/wp-content/uploads/2012/07/browse-packages.png)
 3. Package Control will automatically install Packages according to 
Package%20Control.sublime-settings

---

## Post Installation For Linting (**Linux**) 

##### Installing NPM & NodeJs 

```
sudo apt-get install nodejs-legacy
sudo apt-get install npm
```
##### Linting JavaScript

```
sudo npm install -g jshint 
```

#### Linting CSS

```
sudo npm install -g csslint
```

#### Linting PHP
```
sudo apt-get install -y php7.0 
```
or if you want to install php extentension for PHP Development

```
sudo apt-get install libapache2-mod-php7.0 php7.0-cli php7.0-common php7.0-mbstring php7.0-gd php7.0-intl php7.0-xml php7.0-mysql php7.0-mcrypt php7.0-zip php7.0-curl
```

#### Linting HTML5
```
wget https://github.com/htacg/tidy-html5/releases/download/5.4.0/tidy-5.4.0-64bit.deb
sudo dpkg -i tidy-5.4.0-64bit.deb
```

## Post Installation For Linting (**MAC**) 

##### Installing NPM & NodeJs 

```
brew install nodejs
brew install npm
```
##### Linting JavaScript

```
sudo npm install -g jshint 
```

#### Linting CSS

```
sudo npm install -g csslint
```

#### Linting PHP
```
brew install homebrew/php/php72
```

Be Sure to include Php72 in PATH.

#### Linting HTML5
```
brew install tidy-html5
```

#### Prefrences.sublime-setting

```
{
	"always_show_minimap_viewport": true,
	"caret_style": "wide",
	"color_scheme": "Packages/Boxy Theme/schemes/Boxy Tomorrow.tmTheme",
	"dpi_scale": 2.0,
	//  For Linux Kde
	"font_face": "Noto Sans",
	"font_size": 14,
	"gutter_theme": "Packages/Boxy Theme/extras/SublimeLinter/Boxy.gutter-theme",
	"highlight_line": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"line_padding_bottom": 2,
	"line_padding_top": 2,
	"theme": "Boxy Tomorrow.sublime-theme",
	"theme_accent_blue": true,
	"theme_autocomplete_item_selected_colored": true,
	"theme_bar": true,
	"theme_button_rounded": true,
	"theme_dirty_colored_always": true,
	"theme_find_panel_close_hidden": true,
	"theme_find_panel_font_xl": true,
	"theme_find_panel_materialized": true,
	"theme_find_panel_padding_xl": true,
	"theme_find_panel_size_xl": true,
	"theme_font_xl": true,
	"theme_grid_border_size_xl": true,
	"theme_icon_button_highlighted": true,
	"theme_icons_materialized": true,
	"theme_minimap_viewport_opacity_xxh": true,
	"theme_popup_border_visible": true,
	"theme_quick_panel_border_visible": true,
	"theme_quick_panel_item_selected_colored": true,
	"theme_quick_panel_size_xl": true,
	"theme_scrollbar_colored": true,
	"theme_sidebar_border": true,
	"theme_sidebar_font_xl": true,
	"theme_sidebar_heading_bold": true,
	"theme_sidebar_highlight_selected_text_only": true,
	"theme_sidebar_highlight_text_only": true,
	"theme_sidebar_indent_top_level_disabled": true,
	"theme_sidebar_size_xl": true,
	"theme_size_xl": true,
	"theme_statusbar_font_xl": true,
	"theme_statusbar_label_bold": true,
	"theme_statusbar_size_xl": true,
	"theme_tab_highlight_text_only": true,
	"theme_tab_selected_filled": true,
	"theme_tab_size_xxl": true,
	"theme_tooltips_font_xl": true,
	"theme_unified": true
}
```