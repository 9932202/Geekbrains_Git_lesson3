## Инструкция
Изменения файла для загрузки на github - подтверждаю эти изменения!!!  

и еще раз меняю текст для отправки на удаленный репозиторий. 

Предлагаю СОЮ ПОМОЩЬ вашему проекту 


# Команда инициализации Гит
git init - команда инициализации гита 

# Добавление файлов в репозиторий  
git add ** (2 первые буквы из названия файла + TAB) - Команда добавляет файл в отслеживаемые гитом. 

git add .   - Команда добавляет все имеющиеся файлы в папке в отслеживаемые гитом. 

.gitignore - создаем этот файл и в него записываем имена файлов, которые гит не будет отслеживать. Обычно это или рисунки или большие файлы кода. 

# Сохранение коммита 
* git commit -m "инфо о том что сделали" - сохраниние коммита.  Эта команда требует предварительно команды git add .   или git add name_file 

* git commit -a -m "инфо о том что сделали" -  тоже сохраняет коммит, но не требует перед этим добавлять файл.  **Важно, что работает только после того как гиту объяснили, какие файлы отслеживать , а какие игнорить**

# Перемещение между коммитами и ветками
git checkout - это команда перемещения. 
Можно перемещаться в коммиты.  тогда нужно набрать : git checkout ****  (4 первие цифры коммита)

или между ветками : git checkout name_branch

# Как увидеть все коммиты?
git log - позволяет увидеть все коммиты
git log --graph - позволяет увидеть все коммиты с графическим представлением
