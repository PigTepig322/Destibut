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




    Панель Source Control в Visual Studio Code находится в нижней части редактора и активируется с помощью иконки Git (выглядит как ветка). Нажмите на эту иконку, чтобы открыть панель Source Control.
    Если у вас уже есть Git-репозиторий, он автоматически отобразится в панели Source Control. Если нет, вы можете инициализировать новый Git-репозиторий в нужном каталоге с помощью команды "git init" в командной строке терминала VS Code или через встроенную функцию VS Code "Initialize Repository".
    Когда вы открываете новый проект, VS Code автоматически открывает панель Source Control и делает первый коммит "Initial Commit" с указанием всех файлов проекта. Эти файлы будут отображены в списке изменений.
    Просмотрите список изменений в панели Source Control. Определите, какие файлы вам нужно добавить в ваш следующий коммит, какие файлы изменены, а какие еще не отслеживаются Git.
    Кликните по файлу, чтобы просмотреть изменения в режиме сравнения с предыдущей версией. Используйте команды "Stage Changes" (добавить изменения в индекс) или "Discard Changes" (отменить изменения), чтобы изменить состояние файла.

    Чтобы добавить файлы коммит, введите сообщение коммита в поле ввода внизу панели Source Control. Нажмите на кнопку "Commit" (Фиксировать изменения) для создания нового коммита с выбранными файлами.
    Используйте кнопки "Push" (Загрузить изменения на сервер) и "Pull" (Загрузить изменения с сервера), чтобы обновить свой локальный репозиторий или отправить коммиты на удаленный репозиторий.
    Чтобы переключиться на другую ветку Git или создать новую ветку и начать работу в ней, используйте список веток.

Мы привели варианты часто используемых действий при работе с панелью Source Control. Теперь рассмотрим другие возможности VS Code.

mkdir advanced-git-lab
cd advanced-git-lab
git init

rem Создаём сложную структуру папок
mkdir src\frontend
mkdir src\backend
mkdir src\shared
mkdir docs\api
mkdir docs\architecture
mkdir docs\deployment
mkdir tests\unit
mkdir tests\integration
mkdir tests\e2e

rem Создаём файл с типами TypeScript
(
echo export interface User {
echo   id: string;
echo   email: string;
echo   profile: UserProfile;
echo }
echo.
echo export interface UserProfile {
echo   firstName: string;
echo   lastName: string;
echo   preferences: UserPreferences;
echo }
echo.
echo export interface UserPreferences {
echo   theme: 'light' ^| 'dark';
echo   notifications: boolean;
echo }
) > src\shared\types.ts

git add .
git commit -m "Initial project structure with shared types"

git checkout -b refactor/types-restructure

(
echo export namespace UserTypes {
echo   export interface IUser {
echo     uuid: string;
echo     email: string;
echo     profile: IUserProfile;
echo     metadata: UserMetadata;
echo   }
echo.
echo   export interface IUserProfile {
echo     personalInfo: PersonalInformation;
echo     settings: UserSettings;
echo   }
echo.
echo   export interface PersonalInformation {
echo     firstName: string;
echo     lastName: string;
echo     birthDate?: Date;
echo   }
echo.
echo   export interface UserSettings {
echo     theme: ThemeMode;
echo     notificationSettings: NotificationConfig;
echo   }
echo.
echo   export type ThemeMode = 'LIGHT' ^| 'DARK' ^| 'AUTO';
echo.
echo   export interface NotificationConfig {
echo     email: boolean;
echo     push: boolean;
echo     sms: boolean;
echo   }
echo.
echo   export interface UserMetadata {
echo     createdAt: Date;
echo     updatedAt: Date;
echo     version: number;
echo   }
echo }
) > src\shared\types.ts

git add .
git commit -m "Refactor: complete type system restructuring with namespaces"

git checkout main
git checkout -b feature/advanced-auth

(
echo export interface User {
echo   id: string;
echo   email: string;
echo   profile: UserProfile;
echo   auth: AuthInfo;
echo }
echo.
echo export interface UserProfile {
echo   firstName: string;
echo   lastName: string;
echo   preferences: UserPreferences;
echo   security: SecuritySettings;
echo }
echo.
echo export interface UserPreferences {
echo   theme: 'light' ^| 'dark' ^| 'system';
echo   notifications: boolean;
echo   language: string;
echo }
echo.
echo export interface AuthInfo {
echo   roles: string[];
echo   permissions: string[];
echo   lastLogin: Date;
echo   mfaEnabled: boolean;
echo }
echo.
echo export interface SecuritySettings {
echo   twoFactorAuth: boolean;
echo   loginAlerts: boolean;
echo   sessionTimeout: number;
echo }
) > src\shared\types.ts

git add .
git commit -m "Feat: add advanced authentication types and security settings"

git checkout main
git merge refactor/types-restructure
git merge feature/advanced-auth  rem Здесь будет сложный конфликт

(
echo export namespace UserManagement {
echo   export interface IUser {
echo     uuid: string;
echo     email: string;
echo     profile: IUserProfile;
echo     auth: AuthInfo;
echo     metadata: UserMetadata;
echo   }
echo.
echo   export interface IUserProfile {
echo     personalInfo: PersonalInformation;
echo     settings: UserSettings;
echo     security: SecuritySettings;
echo   }
echo.
echo   export interface PersonalInformation {
echo     firstName: string;
echo     lastName: string;
echo     birthDate?: Date;
echo   }
echo.
echo   export interface UserSettings {
echo     theme: ThemeMode;
echo     notificationSettings: NotificationConfig;
echo     language: string;
echo   }
echo.
echo   export interface AuthInfo {
echo     roles: string[];
echo     permissions: string[];
echo     lastLogin: Date;
echo     mfaEnabled: boolean;
echo   }
echo.
echo   export interface SecuritySettings {
echo     twoFactorAuth: boolean;
echo     loginAlerts: boolean;
echo     sessionTimeout: number;
echo   }
echo.
echo   export type ThemeMode = 'LIGHT' ^| 'DARK' ^| 'AUTO';
echo.
echo   export interface NotificationConfig {
echo     email: boolean;
echo     push: boolean;
echo     sms: boolean;
echo   }
echo.
echo   export interface UserMetadata {
echo     createdAt: Date;
echo     updatedAt: Date;
echo     version: number;
echo   }
echo }
) > src\shared\types-resolved.ts

@echo off
rem Скрипт для создания 50 коммитов с постепенным внесением бага

for /l %%i in (1,1,50) do (
  echo // Commit %%i - Working feature > feature.js
  
  if %%i EQU 25 (
    echo // BUG: Memory leak introduced here >> feature.js
    git add feature.js
    git commit -m "feat: add optimization (BUG INTRODUCED)"
  ) else if %%i EQU 40 (
    echo // Performance improvement >> feature.js
    git add feature.js
    git commit -m "perf: enhance performance"
  ) else (
    git add feature.js
    git commit -m "chore: update feature %%i"
  )
)

git bisect start
git bisect bad HEAD
git bisect good HEAD~50
git bisect run test_bug.bat

mkdir main-project
cd main-project
git init

rem Добавляем субмодули (замените URLs на реальные)
git submodule add https://github.com/user/shared-lib.git libs\shared
git submodule add https://github.com/user/auth-service.git services\auth
git submodule add https://github.com/user/ui-components.git frontend\components

rem Инициализируем и обновляем все субмодули
git submodule update --init --recursive

rem Обновляем конкретный субмодуль до версии v2.0.0
cd libs\shared
git checkout v2.0.0
cd ..\..
git add libs\shared
git commit -m "Update shared lib to v2.0.0"

rem Массовое обновление всех субмодулей до последнего тега
git submodule foreach "git checkout $(git describe --tags --abbrev=0)"

@echo off
echo Running advanced pre-commit checks...

rem Проверка на наличие debug-кода
git diff --cached --name-only | findstr /R "console\.debug debugger TODO" >nul
if %ERRORLEVEL% EQU 0 (
  echo ❌ Found debug code or TODOs in staged files
  exit /b 1
)

rem Проверка сложности функций (упрощённая версия для Windows)
for /f %%f in ('git diff --cached --name-only') do (
  if exist "%%f" (
    findstr /C:"function" "%%f" | find /c /v "" > complexity.tmp
    set /p lines=<complexity.tmp
    if !lines! GTR 50 (
      echo ❌ Found functions that are too complex in %%f
      del complexity.tmp
      exit /b 1
    )
  )
)

rem Проверка на медленные DOM-операции
git diff --cached --name-only | findstr /R "innerHTML eval( document\.write" >nul
if %ERRORLEVEL% EQU 0 (
  echo ❌ Found potentially slow DOM operations
  exit /b 1
)

echo ✅ All pre-commit checks passed!
exit /b 0

@echo off
echo Running post-merge tasks...

rem Проверка миграций базы данных
git diff HEAD@{1} HEAD --name-only | findstr /C:"database/migrations" >nul
if %ERRORLEVEL% EQU 0 (
  echo 📦 Database migrations detected. Running migrations...
  rem npm run db:migrate
)

rem Обновление зависимостей
git diff HEAD@{1} HEAD --name-only | findstr /C:"package.json" >nul
if %ERRORLEVEL% EQU 0 (
  echo 📦 Package.json changed. Installing dependencies...
  rem npm install
)

rem Перезапуск сервисов
git diff HEAD@{1} HEAD --name-only | findstr /C:"src/" >nul
if %ERRORLEVEL% EQU 0 (
  echo 🔄 Source code changed. Restarting development server...
  rem pm2 restart app
)

git checkout -b develop

git checkout -b feature/user-dashboard
git checkout -b feature/payment-integration
git checkout -b feature/analytics

git checkout -b refactor/performance
git checkout -b refactor/architecture

git checkout -b experiment/new-ui-framework
git checkout -b experiment/microservices

git checkout feature/user-dashboard

rem Имитируем долгую разработку с 10 коммитами
for /l %%i in (1,1,10) do (
  echo // Feature work %%i >> dashboard.js
  git add dashboard.js
  git commit -m "feat: dashboard progress %%i"
  
  rem Каждые 3 коммита обновляемся с develop
  set /a mod=%%i %% 3
  if !mod! EQU 0 (
    git fetch origin
    git rebase origin/develop
  )
)

rem Интерактивный rebase для очистки истории
git rebase -i HEAD~10

git lfs install

rem Отслеживаем большие файлы
git lfs track "*.psd"
git lfs track "*.ai"
git lfs track "*.mp4"
git lfs track "*.zip"
git lfs track "*.pdf"

rem Создаём тестовые большие файлы (нужен fsutil)
fsutil file createnew large-asset.bin 104857600  rem 100MB
fsutil file createnew design-resource.psd 52428800  rem 50MB

git add .
git commit -m "Add large binary assets with LFS"

rem Основная работа
git worktree add ..\hotfix-branch hotfix
git worktree add ..\experiment-branch experiment
git worktree add ..\docs-update docs

rem Параллельная работа в разных директориях
cd ..\hotfix-branch
rem Исправление критического бага

cd ..\experiment-branch
rem Эксперименты с новой функциональностью

cd ..\docs-update
rem Обновление документации

rem Управление worktree
git worktree list
git worktree remove ..\hotfix-branch

@echo off
echo 🔄 Syncing all branches...

git fetch --all --prune

for /f "tokens=*" %%b in ('git branch -r ^| findstr /v HEAD') do (
  for /f "tokens=2 delims=/" %%c in ("%%b") do (
    git branch -f %%c %%b 2>nul || echo.
  )
)

echo ✅ All branches synced!
