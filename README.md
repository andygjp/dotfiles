# README

Dotfiles managed by [chezmoi](https://chezmoi.io/)

# Instructions

Take a look here for detailed instructions:
* [How-to](https://www.chezmoi.io/docs/how-to/)
* [Reference](https://www.chezmoi.io/docs/reference/)

## TL;DR

1. Install chezmoi and Git
2. Checkout this repo `chezmoi init git@github.com:andygjp/dotfiles.git`
3. Compare the differences `chezmoi diff`
4. And apply the changes if you are happy with them `chezmoi apply`
5. Update your dotfiles to the latest copies `chezmoi update`
6. Make a change to a managed file `chezmoi edit ~/.zshrc`
7. Apply the change `chezmoi apply`
8. Share the changes to this repo
```shell script
chezmoi source -- add .
chezmoi source -- commit -m "latest change"
chezmoi source -- push
# or you could issue 'chezmoi cd' and use git normally
```
