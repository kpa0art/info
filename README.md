
## Установка zsh

1) sudo apt install zsh
2) Вызвать консоль.
3) Зайти в параметры -> команда -> запускать другую команду вместо моей оболочки. Написать zsh.
4) перейти в домашнюю папку. 
5) nano .zshrc
6) Редактировать строку: ZSH_THEME="agnoster"
7) Установить zsh-autosuggestions: 
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
И добавить плагин в .zshrc:
```bash
plugins=(zsh-autosuggestions)
```
8) Добавить шрифты.
Скачать шрифты по [ссылке](https://linktodocumentation)
Перекинуть содержимое fonts в ~/.local/share/fonts
Запустить команду
```bash
fc-cache -f -v
```



