# Installation

## Packages required: git and stow

Git
`pacman -S git`
Stow
`pacman -S stow`

First, check out the dotfiles repo in your `$HOME` directory using git

`$ git clone git@github.com/dreamsofautonomy/dotfiles.git`

`$ cd dotfiles`

then use GNU stow to create symlinks

`$ stow .`

After this all your dotfiles will be symlinks, i also included various fonts inlcuing serif, sans, mono, nerd, emojis, japanese, chinese and korean characters fallback fonts. 
Pretty easy and fast. theres no `sh` script or anything, but you can install the packages from the names in .config, there's not a lot of packages, just the basics for hyprland.

Shoutout to @dreamsofautonomy! His youtube <a href="https://youtu.be/y6XCebnB9gs?si=VmvSejS6zAFgX9H3">video</a> explains perfectly gnu stow in depth.
