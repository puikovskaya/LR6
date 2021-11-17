# Лабораторная работа №6
После регистрации на GitHub и установки Git созданием копию выданного репозитория в личное хранилище (Значек Fork)
Для начала работы необходимо настроить клиент git введя имя пользователя и командами `email git config --global user.name <username>` и `git config --global user.email <email>`

![image](Screenshots/git_config.png)

Затем необходимо клонировать удаленный репозиторий на компьютер командой `git clone <url>`

![image](Screenshots/git_clone.png)

Добавляем файл через интерфейс GitHub

![image](Screenshots/added_file_github_interface.png)

Подтягиваем изменения из удаленного репозитория командой `git pull`

![image](Screenshots/git_pull.png)

Получаем историю операций из каждой ветки командой `git log`. Переключение веток с помощью `git checkout`

![image](Screenshots/git_log_master.png)
![image](Screenshots/git_log_branch1.png)

Выполняем слияние в ветку master командой `git merge <branch>`

![image](Screenshots/git_merge.png)

Происхдит конфликт, для решения вручную меняем содержимое файла

![image](Screenshots/before_merge.png)
![image](Screenshots/after_merge.png)

Для индексирования файла используем `git add` и комита `git commit -m <message>` 

![image](Screenshots/commit_merge.png)

Затем необходимо удалить побочную ветку из локального репозитория `git branch -d <branch>` и удаленного репозитория `git push <url> --delete <branch>`

![image](Screenshots/delete_branch1.png)

Делаем несколько изменений и фиксируем их с помощью `git add` и `git commit`

![image](Screenshots/git_new_commits.png)

Необходимо сделать хард ресет коммита, для этого я сделал специальный коммит, открыт лог и командой `git reset --hard <commit>` откатился до предыдущей версии

![image](Screenshots/git_hard_reset.png)

Создал новую ветку для отчета и сразу переключился на нее `git checkout -b report` 

![image](Screenshots/git_hard_reset.png)

Затем принялся писать отчет в файле README.md, использую Markdown синтаксис.  

![image](Screenshots/new_branch_report.png)

Получаем итоговую историю операций с помощью `git log`

![image](Screenshots/last_log.png)

После окончания написания отчета произвел команды `git add *` и `git commit -m "<text>"` и отправил изменения в удаленный репозиторий `git push <rep> <branch>`



