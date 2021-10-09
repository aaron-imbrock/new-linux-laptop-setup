# Install necessary packages

```bash

sudo apt update
sudo apt-get install -y software-properties-common apt-transport-https curl git vim build-essential
```

Refer to https://github.com/aaron-imbrock/dotfiles 

## VSCODE
```bash
curl -sSL https://packages.microsoft.com/keys/microsoft.asc | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
```
## NodeJS
```bash
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo bash -
sudo apt-get install -y nodejs

```
