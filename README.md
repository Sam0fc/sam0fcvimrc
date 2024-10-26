# Sam0fc nvim config
- Targeted for editing ipynb notebooks and pdflatex documents for Environmental Science and Computer Vision. 
- Using Kitty on Ubuntu 22.04 with Nvim stable. 
- Using Zathura as a pdf viewer, firefox as browser. 
- Based on quarto-nvim-kickstarter.

## What does what?

## Tex
- Vimtex with its own highlighting, displaying to Zathura
- img-clip to paste images into files
- nabla.nvim to make maths looks nice (it's not great as configured rn)

## images
- magick to provide bindings to 
- imagemagick to be able to use
- Image.nvim to display images in Kitty (and inline with molten) - which is why i use kitty - wezterm and alacritty don't support inline images afaik.

## notebooks 
- Molten for running python 
- Jupytext to convert .ipynb into markdown
- Quarto for convenient rendering in markdown notebooks
- Otter for LSP via Quarto

## file tree
- oil for general use 
- nvim tree for sidebar 
- projections for managing project files

## convenience features
- alpha for startup
- bigfile for disabling LSP in bigfiles
- Whichkey for displaying keybinds
- Oil for file exploration
- Telescope for fuzzy search
- Spectre for cross project search
- Treesitter for highlighting 
- nvim surround to help manage quotes and brackets
- toggleterm to quickly use the terminal
- vim-slime to send things to terminals

## inconvenience features
- hardtime to help me use vim motions
- screenkey to visualise vim shortcuts

## LSP, completion, speed
- nvim-cmp for completion
- LuaSnips for snippets
- nvim-conform to format 

## git 
- octo nvim for managing git issues
- git blame for blame
- git conflict to visualise conflicts  

## AI
- copilot.lua for AI completion

## package managing 
- Lazy for package management
- Mason for LSP management 

## ui
- dropbar for "breadcrumbs"
- winbar

## visuals
- Catpuccin Mocha color theme  
- todo comments for highlighting of comments
- nvim colorizer for colour highlighting

