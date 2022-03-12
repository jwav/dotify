Dotify is a tool meant to easily convert a local dotfile or dotfolder into a symlink after moving said dotfile/folder into a designated "dotfiles" folder.

For instance, let's suppose that:

- The user has a ~/dotfiles folder holding dotfiles liable to be shared between multiple computers, via a github repo
- The user has a ~/.foorc dotfile

`$ dotify ~/.foorc ~/dotfiles`

Would replace ~/.foorc with a symlink after having copied it into ~/dotfiles

At least that's the plan for now

