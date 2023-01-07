### Instructions Windows

1. Install https://github.com/junegunn/vim-plug
2. Open Nvim and type: ``` :echo stdpath('config') ``` this will display the Path for init.vim
3. If is not created, go to the Path and create Appdata/Local/nvim folder.
![image](https://user-images.githubusercontent.com/91075814/211160078-060dac9b-8efd-49c8-b52e-8360b6d72c79.png)
4. Put the init.vim file from my repo
5. Go to terminal on that path and execute ```nvim init.vim``` and type ``` :PlugInstall! ``` then press Intro
6. If dracula theme gives and error, delete ``` colorscheme dracula ```
7. Install Dracula theme ``` :Plug 'Mofiqul/dracula.nvim'```
8. Add ``` colorscheme dracula ``` to init.vim again

### Advise
I have choosen my personal commands, you can also modify by yourself in the file (line 22)
For install the commands with Plug is highly recommend see the documentation of Plug https://github.com/junegunn/vim-plug

#### Theme
Is required install dracula theme

#### Execute nodejs command = Shift + Z

