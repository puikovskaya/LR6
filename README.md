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
8. Исправляем причину конфликта
![Снимок экрана (569)](https://user-images.githubusercontent.com/94530694/142677967-286c5efa-9fbb-46a7-89f8-f058f8618c7c.png)
![Снимок экрана (568)](https://user-images.githubusercontent.com/94530694/142678044-a0903768-b4b4-4660-968e-0d73ef0e913d.png)
9.Добавляем содержимое рабочего каталога в индекс для последующего коммита и проверяем, исправленна ли ошибка
![Снимок экрана (570)](https://user-images.githubusercontent.com/94530694/142679851-053fe329-35b3-4282-87c1-2d58e0899108.png)
10. Удаляем побочную ветку master
![Снимок экрана (571)](https://user-images.githubusercontent.com/94530694/142680357-a9d918ae-f3d8-41f5-bda7-4c41fe6357a6.png)
11. Делаю изменение в файле mergefile.txt и коммичу его
![Снимок экрана (572)](https://user-images.githubusercontent.com/94530694/142685924-83d9f4c0-1665-40a3-acfe-d582366f45da.png)
12. Делаем "хард" коммит
![Снимок экрана (573)](https://user-images.githubusercontent.com/94530694/142686236-0adad8bd-ef43-4132-a3d5-1127f7378aef.png)
13. Создаём ветку для отчёта и переходим в неё
![Снимок экрана (574)](https://user-images.githubusercontent.com/94530694/142686681-24cf9deb-5c9c-4797-8cbf-487cc6692064.png)
14. Загружаем ветку в удалённый репозиторий
![Снимок экрана (575)](https://user-images.githubusercontent.com/94530694/142687333-5d9e0f6a-52b5-4b8c-96e1-84ddb62ac4ce.png)
15. Лог комманд
git config global user.name/email
git clone https://github.com/puikovskaya/LR6
cd LR6
git pull
git reflog --all
git log -p
git branch -r
git checkout report
git checkout branch1
git merge master
git diff
git add mergefile.txt
git status
git push --set-upstream origin report
16. История коммитов
