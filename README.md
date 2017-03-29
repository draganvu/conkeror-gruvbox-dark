## Conkeror - Gruvbox-dark-soft theme

This is just a personal attempt to recreate the Gruvbox theme
for Conkeror Web browser. I use the Gruvbox Dark theme with soft
contrast everywhere so I decided to make this theme as there
are not many themes available for Conkeror.

This is a work in progress. I do not use Tabs so that feature 
is not supported. I have just themed the minibuffer and modeline.

## Gruvbox
This [theme](https://github.com/morhetz/gruvbox) was orginally 
created for Vim by [Pavel Pertsev](https://github.com/morhetz).

## Usage
Download the theme:

```
mkdir -p ~/.conkerorrc/themes
cd ~/.conkerorrc/themes
git clone https://github.com/draganvu/conkeror-gruvbox-dark.git 
~/.conkerorrc/themes/gruvbox-dark-soft
```

Add this somewhere in your conkeror config:

```javascript
theme_load_paths.unshift("~/.conkerorrc/themes/");
theme_unload("default");
theme_load("gruvbox-dark-soft");
```

## Acknowledgments
I used the default conkeror theme as a template. This theme
can be found in the conkeror source at: 
`/conkeror/style/default/`.

There used to be a blackened theme available with Conkeror. 
This is no longer the case but it can still be found 
[here](http://repo.or.cz/conkeror.git/tree/a38b3a3630ebf85a403207b37220cee9790d3a82:/style/blackened).

[Zenburn](https://github.com/ivoarch/conkeror-theme-zenburn) 
Conkeror theme by [Ivaylo Kuzev](https://github.com/ivoarch).

## License
GPL v3+
