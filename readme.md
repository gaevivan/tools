Запуск eslint 

npx eslint ./src/app --ext .ts > eslint_error.log

Создание angular-project

ng new cfu --directory=frontend --routing=true --skipGit=true --skipInstall=true --style=css --commit=false --minimal=true

Добавление eslint в angular-project

npm install eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev
echo {} > .eslintrc.json

Добавление текста в конце файла в linux

echo <text> >> <filename>

Добавление пустой строки в конец файла в linux

echo >> <filename>

Добавление ng в PATH

alias ng="~/node_modules/@angular/cli/bin/ng"

Если ангуляр-приложение не обновляется при изменении файлов

npm install --save @ngtools/webpack@1.2.4

Папку с готовым проектом добавить как новый репозиторий в гитлаб

git init 
touch README.md 
git add . 
git commit -m "init" 
git push --set-upstream git@gitlab.com:gaevivan/reponame.git master

Папку с готовым проектом добавить как новый репозиторий в гитлаб

git init 
touch README.md 
git add . 
git commit -m "init" 
git push --set-upstream git@gitlab.com:gaevivan/reponame.git master

Установка choco на windows через powershell под админом

Set-ExecutionPolicy Bypass -Scope Process -Force; `
  iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

Соединение с github через https

git remote set-url origin https://github.com/gaevivan/reponame
