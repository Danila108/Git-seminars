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
=======
Просмотр изменений
git status              # показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)
git diff                # сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ)
git diff --color-words  # сравнить рабочую директорию и индекс, показать отличия в словах (неотслеживаемые файлы ИГНОРИРУЮТСЯ)
git diff index.html     # сравнить файл из рабочей директории и индекс
git diff HEAD           # сравнить рабочую директорию и коммит, на который указывает HEAD (неотслеживаемые файлы ИГНОРИРУЮТСЯ)
git diff --staged       # сравнить индекс и коммит с HEAD
git diff master feature # посмотреть что сделано в ветке feature по сравнению с веткой master
git diff --name-only master feature # посмотреть что сделано в ветке feature по сравнению с веткой master, показать только имена файлов
git diff master...feature # посмотреть что сделано в ветке feature с момента (коммита) расхождения с master

