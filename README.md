README.md — это ключевой документ в репозиториях, особенно на GitHub. Он содержит инструкцию для программного продукта.
student@ws535-14:~/Документы/git$ git clone https://github.com/PigTepig322/Kazuha.git
Клонирование в «Kazuha»...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 13 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Получение объектов: 100% (13/13), 5.02 КиБ | 2.51 МиБ/с, готово.
student@ws535-14:~/Документы/git$ nano
student@ws535-14:~/Документы/git$ nano README.md
student@ws535-14:~/Документы/git$ nano gl.py
student@ws535-14:~/Документы/git$ git add -m "поставил коммент"
fatal: не найден git репозиторий (или один из родительских каталогов): .git
student@ws535-14:~/Документы/git$ cd Kazuha
student@ws535-14:~/Документы/git/Kazuha$ git add -m "поставил коммент"
error: unknown switch `m'
использование: git add [<опции>] [--] <спецификатор-пути>...

    -n, --dry-run         пробный запуск
    -v, --verbose         быть многословнее

    -i, --interactive     интерактивный выбор
    -p, --patch           интерактивный выбор блоков
    -e, --edit            отредактировать текущий файл списка изменений и применить его
    -f, --force           разрешить добавление игнорируемых иначе файлов
    -u, --update          обновить отслеживаемые файлы
    --renormalize         перенормализировать концы строк (EOL) отслеживаемых файлов (подразумевает -u)
    -N, --intent-to-add   записать только факт, что путь будет добавлен позже
    -A, --all             добавить изменения из всех отслеживаемых и неотслеживаемых файлов
    --ignore-removal      игнорировать пути удаленные из рабочего каталога (тоже, что и --no-all)
    --refresh             не добавлять, только обновить индекс
    --ignore-errors       пропускать файлы, которые не могут быть добавлены из-за ошибок
    --ignore-missing      удостовериться, что даже недостающие файлы будут проигнорированы при  пробном запуске
    --sparse              allow updating entries outside of the sparse-checkout cone
    --chmod (+|-)x        переопределить бит выполнения на указанных файлах
    --pathspec-from-file <файл>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character

student@ws535-14:~/Документы/git/Kazuha$ git add README.md
student@ws535-14:~/Документы/git/Kazuha$ git commit -m "Комментарий"
[main ffdbd7a] Комментарий
 Committer: Password=1 <student@ws535-14.edu.local>
Ваше имя или электронная почта настроены автоматически на основании вашего
имени пользователя и имени машины. Пожалуйста, проверьте, что они 
определены правильно.
Вы можете отключить это уведомление установив их напрямую:

    git config --global user.name "Ваше Имя"
    git config --global user.email you@example.com

После этого, изменить авторство этой коммита можно будет с помощью команды:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
student@ws535-14:~/Документы/git/Kazuha$ git push -u
Username for 'https://github.com': git push -u origin nnaaadd                   
Password for 'https://git%20push%20-u%20origin%20nnaaadd@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/PigTepig322/Kazuha.git/'
student@ws535-14:~/Документы/git/Kazuha$ git push -u origin nnaaadd
error: src refspec nnaaadd ничему не соответствует
error: не удалось отправить некоторые ссылки в «https://github.com/PigTepig322/Kazuha.git»
student@ws535-14:~/Документы/git/Kazuha$ git push -u origin nnaaadd
error: src refspec nnaaadd ничему не соответствует
error: не удалось отправить некоторые ссылки в «https://github.com/PigTepig322/Kazuha.git»
student@ws535-14:~/Документы/git/Kazuha$ git push -u origin PigTepig322-patch-1
error: src refspec PigTepig322-patch-1 ничему не соответствует
error: не удалось отправить некоторые ссылки в «https://github.com/PigTepig322/Kazuha.git»
student@ws535-14:~/Документы/git/Kazuha$ git branch
* main
student@ws535-14:~/Документы/git/Kazuha$ git checkout nnaaadd
error: pathspec 'nnaaadd' did not match any file(s) known to git
student@ws535-14:~/Документы/git/Kazuha$ git checkout -b nnaaadd
Переключились на новую ветку «nnaaadd»
student@ws535-14:~/Документы/git/Kazuha$ git push -u origin nnaaadd
Username for 'https://github.com': PigTepig322
Password for 'https://PigTepig322@github.com': 
Перечисление объектов: 5, готово.
Подсчет объектов: 100% (5/5), готово.
При сжатии изменений используется до 4 потоков
Сжатие объектов: 100% (2/2), готово.
Запись объектов: 100% (3/3), 340 байтов | 340.00 КиБ/с, готово.
Всего 3 (изменений 0), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
To https://github.com/PigTepig322/Kazuha.git
   e6e25ff..ffdbd7a  nnaaadd -> nnaaadd
branch 'nnaaadd' set up to track 'origin/nnaaadd'.
student@ws535-14:~/Документы/git/Kazuha$ ^C
student@ws535-14:~/Документы/git/Kazuha$ 
