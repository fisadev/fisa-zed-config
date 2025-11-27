# Fisa Zed Config

My personal Zed configuration, inspired by my vim configs

![Demo](demo.gif)

# Installation

Just copy the `config` folder contents into your Zed config folder. 
In linux, that's `/home/YOUR_USER/.config/zed/`.

My config is using the CPMono_v07 font, which you can download here:
https://font.download/font/cpmonov07

And I'm using [Fish](https://fishshell.com/) as shell too.

Both things can be changed if you prefer other shells or fonts, editing the `config/settings.json` file.

# Some custom key mappings

A few key mappings I added:

- `alt + left/right arrows` to switch between tabs.
- `, e` to show the fuzzy file finder.
- `, g` to show the fuzzy project symbols (classes, functions, etc) finder.
- `, d` go to definition.
- `F2` close any panels and focus on the editor.
- `F3` show files tree, toggle focus between it and the editor.
- `F4` show class browser, toggle focus between it and the editor.
- `ctrl-j` toggle terminal (a default, but I made sure it works in vim's normal mode).
- `ctrl-i` show AI assistant, toggle focus between it and the editor.
