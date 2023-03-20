![](https://github.com/CrystalPhantom/Config-Vim-Settings/blob/93832b0cba38c37e8c4c7cb3f3588f82192102a6/assets/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-03-20%2022-51-03.png)

# Config Vim and basic settings :point_down:

### First you need to understand what vim is :point_up:
 
##### Vim is a free text editor based on the older vi. Now it is a powerful text editor with complete freedom of customization and automation made possible by extensions and add-ons. Vim's user interface can run in pure text mode.


# Table if Contents :point_down:

* [Installation](#installation)





# Installation
We will install vim on linux<br>
__Installed on Fedora Linux!!!__

```vim 
$ sudo dnf update
$ sudo dnf install vim
```

__Installing vim but already on macos!__<br> 
https://macvim.org/


In order to find out the version of vim, go to vim itself

```vim 
$ vim 
```
![](https://github.com/CrystalPhantom/Config-Vim-Settings/blob/f9ac9591e9601ac19a93e6288a0ab4d810341511/assets/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-03-18%2015-14-48.png)

We have checked and Vim version is currently 9.0


# Сommands in Vim terminals
```
i - перейти в режим редактирования 
```
```
yy - копирование текущей строки в буфер 
```
```
v - выделение текста, используется для копирования участков текста 
```
```
y - копировать выделенный текст 
```
```
d - удалить выделенный текст 
```
```
dd - удалить одну строку - на которой курсор
```
```
d 4 d - удалить 4 строки
```
```
р - вставка из буфера под курсором 
```
```
P - вставка из буфера перед курсором 
```
```
u - назад - отменить последнее действие (аля ctrl+z)
```
```
:w - сохранить изменения 
```
```
:x - сохранить все изменения и выйти 
```
```
:q! - выйти без сохранения изменений 
```
