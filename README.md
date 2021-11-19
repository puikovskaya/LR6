# LR6
Лабораторная работа №6
1. Клонируем репозиорий на компьютер
![Снимок экрана (559)](https://user-images.githubusercontent.com/94530694/142600705-478dcbb1-87c5-4e3e-bcdd-9022e7297b13.png)
2. На сайте GitHub создаем файл file и подтягиваем изменения на локальное устройство
![Снимок экрана (560)](https://user-images.githubusercontent.com/94530694/142609562-ce1c8746-4bd5-4f81-aa3f-07ced97bbff1.png)
3. Получаем историю операций для каждой ветки
![Снимок экрана (561)](https://user-images.githubusercontent.com/94530694/142611742-e148d1cf-cc8f-441d-a9e3-69812fd24a8c.png)
4. Смотрим последние изменения
![Снимок экрана (564)](https://user-images.githubusercontent.com/94530694/142668885-47c44cce-1a1b-44ff-a067-da36aea5b6fc.png)
5. Смотрим доступные ветки и переходим в одну из них
![Снимок экрана (565)](https://user-images.githubusercontent.com/94530694/142674047-d374b438-9cc2-4728-99a0-01f462f27375.png)
6. Выполняем слияние и получаем сообщение о конфликте
![Снимок экрана (566)](https://user-images.githubusercontent.com/94530694/142676670-97e859bd-ae6a-40d7-9b10-2d104eeb68d1.png)
7. Выясняем причину конфликта
![Снимок экрана (567)](https://user-images.githubusercontent.com/94530694/142677270-be690e41-f1cb-420a-86d4-3dea77c5e56b.png)
8. Исправляем причину конфликта </br>
![Снимок экрана (569)](https://user-images.githubusercontent.com/94530694/142677967-286c5efa-9fbb-46a7-89f8-f058f8618c7c.png)
![Снимок экрана (568)](https://user-images.githubusercontent.com/94530694/142678044-a0903768-b4b4-4660-968e-0d73ef0e913d.png) </br>
9.Добавляем содержимое рабочего каталога в индекс для последующего коммита и проверяем, исправленна ли ошибка
![Снимок экрана (570)](https://user-images.githubusercontent.com/94530694/142679851-053fe329-35b3-4282-87c1-2d58e0899108.png)
10. Удаляем побочную ветку master </br>
![Снимок экрана (571)](https://user-images.githubusercontent.com/94530694/142680357-a9d918ae-f3d8-41f5-bda7-4c41fe6357a6.png)
11. Делаю изменение в файле mergefile.txt и коммичу его </br>
![Снимок экрана (572)](https://user-images.githubusercontent.com/94530694/142685924-83d9f4c0-1665-40a3-acfe-d582366f45da.png)
12. Делаем "хард" коммит </br>
![Снимок экрана (573)](https://user-images.githubusercontent.com/94530694/142686236-0adad8bd-ef43-4132-a3d5-1127f7378aef.png)
13. Создаём ветку для отчёта и переходим в неё </br>
![Снимок экрана (574)](https://user-images.githubusercontent.com/94530694/142686681-24cf9deb-5c9c-4797-8cbf-487cc6692064.png)
14. Загружаем ветку в удалённый репозиторий
![Снимок экрана (575)](https://user-images.githubusercontent.com/94530694/142687333-5d9e0f6a-52b5-4b8c-96e1-84ddb62ac4ce.png)
15. Лог комманд </br>
git config global user.name/email </br>
git clone https://github.com/puikovskaya/LR6 </br>
cd LR6 </br>
git pull </br>
git reflog --all </br>
git log -p </br>
git branch -r </br>
git checkout report </br>
git checkout branch1 </br>
git merge master </br>
git diff </br>
git add mergefile.txt </br>
git status </br>
git push --set-upstream origin report </br>
16. История коммитов
commit e1ae80abaef948152bc477506022cbca6a81502c (HEAD -> branch1, origin/Report, Report)
Author: Borodina A.P. 4016 <princessnasta02@gmail.com>
Date:   Fri Nov 19 23:07:30 2021 +0300

    New information

diff --git a/mergefile.txt b/mergefile.txt
index 08c29f6..0d1014b 100644
--- a/mergefile.txt
+++ b/mergefile.txt
@@ -4,4 +4,5 @@
 противоречащей
 ветке
 master
+123


commit c5e387796ad19f85de8abb7039ecf4a0e04a913d
Merge: 0f9f50d 569adb8
Author: Borodina A.P. 4016 <princessnasta02@gmail.com>
Date:   Fri Nov 19 22:21:54 2021 +0300

    Merget

commit 569adb810f210ae5081f53994e0c18b3f5370198 (origin/master, origin/HEAD)
Author: Borodina A.P. 4016 <princessnasta02@gmail.com>
Date:   Fri Nov 19 13:17:26 2021 +0300

    Изменение

diff --git a/file b/file
index d00491f..9f358a4 100644
--- a/file
+++ b/file
@@ -1 +1 @@
-1
+123456

commit 5ab2056a4e8ddf83963b4f194a2c450785c889e2
Author: Borodina A.P. 4016 <94530694+puikovskaya@users.noreply.github.com>
Date:   Fri Nov 19 13:15:11 2021 +0300

    Create file

diff --git a/file b/file
new file mode 100644
index 0000000..d00491f
--- /dev/null
+++ b/file
@@ -0,0 +1 @@
+1
