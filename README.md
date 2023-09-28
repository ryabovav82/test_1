Wellcome to my hell!




ssh-keygen -t ed25519 -C "ryabovav82@yandex.ru ” Генерация SSH ключа

cat ~/.ssh/id_ed25519.pub - связывание SSH-ключа и GitHub-аккаунта - копирует ключ

git remote add - Привязать удалённый репозиторий к локальному

git remote add origin [git@github.com](mailto:git@github.com):%ИМЯ_АККАУНТА%/first-project.git

git remote set-url origin [git@github.com](mailto:git@github.com):ryabovav82/dns_project.git

git remote -v - убеждаемся что связаны

git config --global [user.name](http://user.name/) "Ryabov Andrey"

git config --global user.email [ryabovav82@yandex.ru](mailto:ryabovav82@yandex.ru)

git init - инициализируем проект, нужно делать из корневой папки проекта

rm -rf .git  - *удалили подпапку .git*

git add . - добавляет все файлы в git

git status - показывает статус файлов

git rm --cached <file> - удаляет файл из git

git commit -m "first commit” -добавление в локальное хранение с комннтарием

git log - вся история

git log —oneline история сокращенная

git checkout ____id_____ - показывает версии по id (для просмотра)

git checkout master - возвращение к последней версии

git revert ____id_____  - отмена commit  :wq

git reset  ____id_____   - удалит все commit выше него без изменений данных

git reset  ____id_____ —hard - удалит все commit выше него со всеми изменениями

git push -u origin main(master) - отправить изменения на удаленный репозиторий