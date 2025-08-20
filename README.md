## NVIM CONFIG

### DOWNLOAD

```console
git clone https://github.com/xrayxv9/xray_config ~/.config/nvim

```

### MAIN SHORTCUT

Before anything, we will refer to space as <leader>, then
here are the most important shortcuts:

 - ```<leader-e>```  :   opens the tree

 - ```<leader-c>```  :   switch from tree to code abd from code to tree

 - ```<C-arrows>```  :   increase or decrease the tree size

 - ```<leader ff>``` :   opens the telescope

 - ```<->```         :   opens the current directory

 - ```<C-\> ```      :   opens/close a terminal

 - ```<C-/>```       :   in normal mode comments a line
                in visual mode comments all the selected line

 - ```<Alt-arrows>```:   Move the selected line (only up and down arrows works)

 - ```<leader-11>``` : Put the 42 student header

 - ```<leader-vc>``` : opens a color picker

 - ```<Ctrl a>``` : close a window opened in the buffer

 - ```<Ctrl arrow>``` : change the opened file to an other one opened in the buffer

 - ```<Ctrl f>``` : Search through all the files and find the word you are searching for

 - ```<leader d>``` : Open the dark themes menu 

 - ```<leader l>``` : Open the light themes menu 

 - ```<leader a>``` : Open the themes menu 



### LITTLE THINGS TO CHANGE

If you want to change the theme you can see all the themes on here:
```https://github.com/folke/tokyonight.nvim```

then do the command:
```console
cd ~/.config/nvim/lua/plugins
nvim tokyo.lua
```
and change the line 6:
```lua
vim.cmd[[colorscheme tokyonight-night]]
to 
vim.cmd[[colorscheme tokyonight-<desired-theme>]]
```
