# Configuración de NVIM desde cero


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
## Necesarios para pluggin y programación 

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
### Instalar Python ultima version
```
sudo apt install python3-pip  
pip install pynvim  
pip3 install --upgrade pynvim  
pip3 install black
```
### Instalar Stylua
```
cargo install stylua
```
### Instalar Lazygit
```
sudo pacman -S lazygit
```
### Instalar Ninja
```
sudo apt-get install ninja-build
```
## Instalar NVIM última versión
```
sudo apt remove neovim -y  
sudo add-apt-repository ppa:neovim-ppa/stable  
sudo apt-get update  
sudo apt-get install neovim
```
### Ubicación de archivo de configuración de Nvim
```
Carpeta de configuración: ~/.config/nvim/
```
