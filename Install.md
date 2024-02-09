# Установка git на Windows, Mac, Linux

### **Все материалы ниже были взяты официального сайта git [Установка git](https://git-scm.com/downloads)**

## Linux
Для установки git на Linux нам понадобится терминал который обычно вызывается связкой клавиш *Ctrl+Alt+T*

### Ubuntu/Debian
`sudo apt-get install git`

### Fedora
`sudo dnf install git`

### Arch linux
`sudo pacman -S git`


## Windows
В Windows можно открыть один из файлов
> [32-bit git for Windows](https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-32-bit.exe)

> [64-bit git for Windows](https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-64-bit.exe)

А можно и через командную строку
`winget install --id Git.Git -e --source winget`

## macOS
Для установки на macOS нужно будет использовать терминал и вписать след команду

`brew install git`

или

`sudo port install git`

---
## Проверка

После устновки следует проверить вписав в терминале команду

`git --version`

можно и

`git version`