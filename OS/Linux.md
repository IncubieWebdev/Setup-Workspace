![INSTRUCTIONS](https://img.shields.io/badge/Instruction-Beta-red.svg?logo=appveyor&style=for-the-badge)

# SETUP Instructions

Instruksi SETUP ini akan membantu kalian untuk mempelajari web development Tutorial incubie dengan menggunakan tools berikut :

* Pilih Text-Editor yang biasa kalian gunakan.
* Install Package Manager([pip](Link), [yarn](Link), [npm](Link))
* Setup git & Github
* Install [python], [NodeJS.]

## Github account
Apa kamu sudah membuat akun Github? Jika belum Maka [SignUp](https://github.com/join) sekarang !

## Git
Untuk meng-Install `git`, pertama-tama buka terminal kalian `Terminal`

Copy perintah line ini.

* Untuk Ubuntu/Debian Distributions : 
```bash
sudo apt-get install -y git
```

* Untuk Fedora/CentOS Distributions :
```bash
# install git dengan DNF
sudo dnf install git
# install git dengan YUM
sudo yum install git
```

* Untuk Arch Linux Distributions :
```bash
sudo pacman -S git
```

## The best Text Editor to Start your journey...
Pilih salah satu.

### Sublime Text 3 is good for you..
* Ubuntu/Debian :
    ```bash
    wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
    echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
    sudo apt-get update
    sudo apt-get install sublime-text
    ```
* Fedora/CentOS :
    ```bash
    sudo dnf install sublime-text
    # or
    sudo yum install sublime-text
    ```
* Arch-Linux :
    ```bash
    sudo pacman -S sublime-text
    ```

### VSCode Powerfull and lightweight..
* Ubuntu/Debian :
download in [here](https://go.microsoft.com/fwlink/?LinkID=760868)
```bash
sudo dpkg -i <file>.deb
sudo apt-get install -f # Install dependencies
```
* Fedora/CentOS :
```bash
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
dnf check-update
sudo dnf install code
# or
yum check-update
sudo yum install code
```
* Arch-Linux :
```bash
yaourt -S visual-studio-code-bin
```
### Atom is Powerfull enough..
* Ubuntu/Debian :
```bash
# Install Atom
sudo dpkg -i atom-amd64.deb
# Install Atom's dependencies if they are missing
sudo apt-get -f install
```
* Fedora/CentOS :
```bash
# On YUM-based distributions
sudo yum install -y atom.x86_64.rpm
# On DNF-based distributions
sudo dnf install -y atom.x86_64.rpm
```
* Arch-Linux :
```bash
sudo pacman -S atom
```

## Oh-my-zsh - Fancy your Terminal
#### via curl
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

#### via wget
```bash
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

Untuk setting selengkapnya check [disini](https://github.com/robbyrussell/oh-my-zsh).

## Install pip, yarn & npm.
* Ubuntu/Debian :
    * Pip :
    ```bash
    apt install python3-pip
    ```
    * yarn :
    ```bash
    sudo apt-get update && sudo apt-get install yarn

    ```
    * npm :
    ```bash
    sudo apt update
    sudo apt install nodejs npm
    sudo apt install npm
    ```
* Fedora/CentOS :
    * npm
    ```bash
    sudo dnf install npm
    #or
    sudo yum install npm
    ```
    * pip
    ```bash
    yum -y install python-pip
    ```
    * yarn
    ```bash
    npm install yarn
    ```
* Arch-Linux :
    * npm
    ```bash
    sudo pacman -S npm
    ```
    * pip
    ```bash
    sudo pacman -S pip
    ```
    * yarn
    ```bash
    npm install yarn
    ```

### Good job youre done !
