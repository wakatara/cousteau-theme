# Cousteau theme for fish shell

Cousteau is a theme forked and modified from the [Chris Morrell's Fish Theme](https://github.com/oh-my-fish/theme-cmorrell.com).

When I was getting started with [fish](https://fishshell.com) Morrell's was the one that seemed the nicest as a base to start with, so I've done some hacking on it to modify it for my purposes. YMMV on whether it works for you or not. Enjoy and please feel free to fold, spindle, mutilate or add features which I'm happy to add via pull request.

## Features

- More minimal base prompt
- Shows compact git status w/ the number of changed files & current branch
- Gives a visual indication when you're logged in via SSH, or logged in as anyone
    but the default user (set the `$default_user` list variable to define your default user)
- Shows indicator if previous command failed
- Shows a bright red "!" if you're logged in as root

## Installation

The best way is to use the excellent fish package manager [fisher](https://github.com/jorgebucaran/fisher) and then just use `fisher add wakatara/cousteau-theme` to get it onto your system.

## Why Cousteau?

I name all my laptops, usually after explorers. Since my latest 2016 Macbook is named Cousteau, and I needed something fishy sounding, it seemed ideal. I hope I can live up to the name I selected. 

