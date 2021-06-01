# Dotfiles

Быстрая настройка окружения для работы


## Fonts

Скачать с [репозитория](https://github.com/tonsky/FiraCode) FiraCode, разархивировать и установить


## VScode

Установка редактора
```bash
sudo snap install --classic code
```

Установка расширений
```bash
./vscode/install.sh
```

Скопировать настройки
```bash
cp ./vscode/settings.json ~/.config/Code/User/settings.json
```


## System utilities

```bash
# обновление
sudo apt update
sudo apt upgrade

# кодеки
sudo apt install ubuntu-restricted-extras libavcodec-extra libdvd-pkg

# доп возможности по настройке
sudo apt install gnome-tweak-tool

# архиваторы
sudo apt-get install p7zip-rar rar unrar unace arj cabextract

# редактор dconf
sudo apt install dconf-editor

# плеер
sudo apt install vlc

# другие программы
sudo apt install curl wget git tree vim nano

# альтернатива терминала - Terminator (https://ubuntu.fandom.com/ru/wiki/Terminator)
sudo apt install terminator python-cairo

# сворачивание в один клик
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'
```

Установка программ:
  - [Chrome](https://www.google.com/intl/ru/chrome/)
  - [Slack](https://slack.com/intl/en-ru/downloads/linux])
  - [Telegram](https://desktop.telegram.org/)
  - [Discord](https://discord.com/download)



## ZSH

```bash
sudo apt install zsh
chsh -s $(which zsh)

sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```
