# Just my Windows Dotfiles and Scripts

To use, ensure the following file/contents exists (adjust for your own paths):

~/.bash_profile

```bash
#!/bin/bash
export PATH=$PATH:~/.scripts
```

To install

```bash
./install
```

## Git


### Up
```bash
git up
```
Instead of having to do git push --set-upstream origin <branchname> to push a new branch just do git up

### edit
```edit
git up
```Shortcut to git commit --amend --no-edit