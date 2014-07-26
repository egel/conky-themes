# Conky Themes

Multiple conky themes to be used in my dotfiles.

## Installation

Download the Git repository and its submodules:

```sh
$ git clone --recursive https://github.com/egel/conky-themes.git ~/.conky-themes
```

## How to use it

If you want to use the `conky_seamod` theme (for instance):

```sh
$ ln -sf ~/.conky-themes/conky_seamod/.conkyrc ~/.conkyrc
```

Then you can just launch conky:
```sh
$ conky -q&
```

You can also provide the path to a given `conkyrc` file:
```sh
$ conky -q -c ~/.conky-themes/conky_seamod/.conkyrc
```
