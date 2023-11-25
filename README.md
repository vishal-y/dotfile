
# DOTFILES

I was wew to Vim just a week ago, I stumbled upon Neovim and NvChad and fell in love. Learning was tough, but the power it offers for coding is incredible. Coming from Visual Studio Code, I've tailored my Neovim setup with basic shortcuts and a touch of VS Code familiarity. Perfect for newcomers making the switch. 

These dotfiles are designed to empower your workflow with a harmonious blend of productivity features, visual appeal, and familiar shortcuts. 😃


**NOTE : Pre-requisites**
- Neovim
- Nvchad
- Git


## Features

- **NvChad Integration** : Seamlessly adopt NvChad's feature-rich Neovim configuration, offering a curated selection of plugins and optimizations for an optimal coding environment
- C++ Development Workflow : Compile and run C++ programs effortlessly using the `<leader>rc `or` <space> + rc` shortcut, keeping the terminal open for post-run interactions.
- DAP Debugger Integration : Debug code with ease using DAP debugger integration. Utilize shortcuts like `<leader>db` or `<space> + db ` to toggle breakpoints and `<leader>dr` or `<space> + dr` to start or continue the debugger.
- Toggle Transparent Mode : Enhance the visual appeal with a toggleable transparent mode for Neovim. Quickly switch between transparent and opaque modes for a customized aesthetic
- VS Code Shortcuts : Feel at home with familiar VS Code-inspired shortcuts, such as `<C-s>` or `<ctrl> + s` for saving in insert mode and `<C-z> or <ctrl> + z` for undoing changes
- Customized Key Mappings : Navigate and edit code effortlessly with a set of customized key mappings, optimizing your workflow for efficiency and comfort.



##

#### The mapping configuration uses the nvim name shorcuts 

- `<C>` -> Ctrl
- `<leader>` -> Space
- `<A>` -> alt
- `<S>` -> shift

- The default mappings are defined in `core.mappings` (`core/mappings.lua`).
- Alternatively, you can use `NvCheatsheet` or `Telescope keymaps` to list all mappings.

More at here :- https://nvchad.com/docs/config/mappings




## Installation

Clone the repository:

```sh
   git clone https://github.com/vishal-y/dotfile.git ~/.config/nvim
```

if you just started overwrite you config file 

## customize
Feel free to customize the configuration further according to your preferences. Explore the `init.lua` file and adjust settings, key mappings, and plugins as needed.

## Screenshots

![code](https://github.com/vishal-y/dotfile/assets/85288372/1e71aa14-2267-4743-9d29-48a65a0e7ad4)
code 👆🏻

![output](https://github.com/vishal-y/dotfile/assets/85288372/a0cad141-af91-441b-9291-c59f6435262a)
output 👆🏻


## Demo

![demo](https://github.com/vishal-y/dotfile/assets/85288372/8738d9c0-a6a7-4060-b4d7-8ca12e8b5ea6)



## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility or anything else just raise an issue or fork this repo :)

##

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

Transform your Neovim experience with these dotfiles. Happy coding :) 



