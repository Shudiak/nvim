# Configuración de NVIM desde cero
<hr></hr>

# Prerequisitos

## Packer Manager
* Npm
* Cargo
* Pacman
* GO

Instalar npm
```
sudo apt install npm
```
Instalar cargo
```
sudo apt install cargo
```
Instalar pacman
```
sudo wget -O /usr/local/bin/pacapt \
https://github.com/icy/pacapt/raw/ng/pacapt
sudo chmod 755 /usr/local/bin/pacapt
sudo ln -sv /usr/local/bin/pacapt /usr/local/bin/pacman || true
```
Instalar go
```
sudo apt install golang-go
```
## Programas varios

### Nodejs
```
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
https://phoenixnap.com/kb/update-node-js-version
```
### Tree sitter
```
npm install tree-sitter
npm install -g tree-sitter-cli
```
### Instalar ripgrep
```
sudo apt-get install ripgrep
```
### Instalar prettier
```
sudo npm install -g prettier
```
### Instalar black
```
sudo npm install -g black
```
### Instalar fd
```
sudo apt install fd-find
```
