![Screenshot 2023-07-06 at 2 56 52 PM](https://github.com/Rumone/JoshNvim/assets/63555633/9a3adb41-a686-4b3c-9d6d-afe3ba7be54e)
> If you can't read the banner it says "JOSH.DEV"

# 🫣 JoshVim 

## Installation
> Note: If you currently have a neovim setup that you would like to keep just rename `~/.config/nvim` to anything you want really
```
mv ~/.config/nvim ~/.config/thisIsMyBackup
```
- Clone the template
  ```
  git clone git@github.com:Rumone/JoshVim.git ~/.config/nvim
  ```

## FAQ
1. What if it doesn't work?

I dont know enuh it works for me. Start a discussion maybe.

2. Why did you overrwrite the entire repo?

I felt it was time to let go of LazyVim and spend hours inventing my own. There are a few more steps involved if you want to use this config by the way (have fun figuring that out).
> You may run into lsp issue because this config doesn't install any by default. run `LspInstall` and chose an lsp yourself the rest should just work out of the box, hopefully.

3. Why is there an apple icon in my status line I run linux?

You machine is secretly a macbook

## Todo
[] Investigate more areas for lazy loading plugins
[] Remove even more plugins if I can
[] Refactor parsers installed. I dont use half of these
[] Enable scope highlighting, Pretty sure that has to do with treesitter
[] Look into a few auto commands that could help my workflow
[] Add documentation then use whichkey to display them. Or I might just create a buffer with all the keymaps that you can access through telescope

## CONTRIBUTING
Just create a PR bro it's not that deep. I will take a look and tell you to change things.
