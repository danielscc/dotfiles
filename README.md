# Installation

## Packages required: git and stow

Git
`pacman -S git`
Stow
`pacman -S stow`

First, check out the dotfiles repo in your $HOME directory using git

`$ git clone git@github.com/dreamsofautonomy/dotfiles.git`
`$ cd dotfiles`

then use GNU stow to create symlinks

`$ stow .`

after this all your dotfiles will be symlinks, pretty easy and fast. I haven't make a sh script or anything, but you can install the packages from the names in .config, there's not a lot of packages, just the basics for hyprland.

shoutout to @dreamsofautonomy, his youtube <a href="https://youtu.be/y6XCebnB9gs?si=VmvSejS6zAFgX9H3">video</a> explains perfectly gnu stow in depth.
