###Install nvm

```bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash
```

Twice I've run this and it didn't source it correctly so add these lines to the end of your .bash_profile:

```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
```

###Install node

```bash
nvm install stable
```
