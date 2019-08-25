ПОЛЕЗНЫЕ ЗАМЕТКИ ПРИ РАБОТЕ С GIT-BASH

1.В командной строке перейдите в локальный репозиторий или клонируйте 
git clone github://path.git

2.Убедитесь, что вы находитесь в ветке по умолчанию:
git checkout master

3.Команда rm -r рекурсивно удалит вашу папку:
git rm -r folder-name

4.Зафиксируйте изменения:
git commit -m "Removed duplicated directory"

5.Нажмите изменения в вашем удаленном хранилище:
git push origin master
