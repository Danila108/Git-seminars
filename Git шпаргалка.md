# Создание репозитория
git init
# Добавим все файлы проекта в наш будующий commit
git add .

Или так

git add --all



# Cоздаем commit. Обязательно указываем комментарий

**Сокраняемся обязательно!**

git commit -m "<комментарий>"

# Версия Гит

git --version

# Журнал изменений
git log

# Показать изменения

git diff

# Представлене
 git config --global user.name 'Имя'

 git config --global user.email 'e-mail'

# Вернутся к прошлым версиям 
 git checkout имя
 
# Вернутся к актуальной версии
git checkout master

# слияние веток

git merge  text_formating

Создать новый репозиторий
git init             # создать новый проект в текущей директории
git init folder-name # создать новый проект в указанной директории
Клонирование репозитория
# клонировать удаленный репозиторий в одноименную директорию
git clone https://github.com/cyberspacedk/Git-commands.git    

# клонировать удаленный репозиторий в директорию «FolderName»
git clone https://github.com/cyberspacedk/Git-commands.git FolderName 

# клонировать репозиторий в текущую директорию
git clone https://github.com:nicothin/web-design.git .   