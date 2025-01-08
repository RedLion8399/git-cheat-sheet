# git-cheat-sheet
These commands are only tested on windows.

## Basig configuration
```bash
git config --global user.name "Paul Jonas Dohle"
git config --global user.email "paul.jonas@dohle-net.de"
```

```bash
git config --global core.editor "code --wait"
git config --global pull.ff only
git config --global init.defaultBranch main
```

## Alias
```bash
git config --global alias.st status
git config --global alias.br branch
git config --global alias.brd "branch -d"
git config --global alias.c commit
git config --global alias.cm "commit -m"
git config --global alias.cam "commit -a -m"
git config --global alias.co checkout
git config --global alias.chb "checkout -b"
git config --global alias.a add
git config --global alias.aa "add ."
git config --global alias.pp "!git pull && git push"
git config --global alias.pb "!git push --set-upstream origin \"$(git rev-parse --abbrev-ref HEAD)\""
```

## SSH
```bash
git config --global gpg.format ssh
```

```bash
git config --global commit.gpgsign true
git config --global tag.gpgsign true
```

```bash
git config --global user.signingkey <your-signing-key>
```
