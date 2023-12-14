# Старт работ с Git и Visual studio code

## Для начала работы необходимо установить VScode и Git. 
➤Установка Git для Windows, MAC, Linux: https://git-scm.com/downloads

Инструкция: https://selectel.ru/blog/tutorials/how-to-install-git-to-windows/

➤Установка VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download

Инструкция: 
https://habr.com/ru/articles/490754/ 

---
### Порядок работ
1. Создаем на компьютере папку для работы.
2. Открываем VSCode — открываем в программе нашу папку.
3. Создаем файл (в конце названия нашего файла добавить .md , чтобы тип файла был для разметки Markdown).
4. Открываем терминал в VSCode 
> Если мы впервые используем гит и не предоставляли имя и email, то необхдимо их ввести. Они будут использоваться для всех репозиториев, с которыми мы будем работать. Это нужно для того, чтобы было понятно, кто вносил коммиты.

Команды для ввода имени и email:

> git config --global user.name "Mona Lisa"

> git config --global user.email "asd@gmail.com"


Чтобы посмотреть, какое имя и email были введены, выполняем следующие команды:

> git config user.name

> git config user.email

5. Нам нужно начать отслеживать нашу папку. Для этого вводим команду:
> git init