user@David-PC MINGW64 ~
$ git --version
git version 2.39.2.windows.1

user@David-PC MINGW64 ~
$ git config --global user.name Paola Briceno

user@David-PC MINGW64 ~
$ git config --global user.email paolabricenov@outlook.com

user@David-PC MINGW64 ~
$ git config -l
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=paolabricenov
user.email=paolabricenov@outlook.com
user.name=Paola

user@David-PC MINGW64 ~
$ ^C

user@David-PC MINGW64 ~
$ ^C

user@David-PC MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/user/.git/

user@David-PC MINGW64 ~ (master)
$ cd

user@David-PC MINGW64 ~ (master)
$ cd ejercicios
bash: cd: ejercicios: No such file or directory

user@David-PC MINGW64 ~ (master)
$ cd desktop/

user@David-PC MINGW64 ~/desktop (master)
$ cd ejercicios/

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ ls
ejercicio1/

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ ls -al
total 24
drwxr-xr-x 1 user 197121 0 Mar  2 13:49 ./
drwxr-xr-x 1 user 197121 0 Mar  2 13:22 ../
drwxr-xr-x 1 user 197121 0 Mar  2 13:50 ejercicio1/

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ git init
Initialized empty Git repository in C:/Users/user/Desktop/ejercicios/.git/

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ ls -al
total 28
drwxr-xr-x 1 user 197121 0 Mar  2 14:52 ./
drwxr-xr-x 1 user 197121 0 Mar  2 13:22 ../
drwxr-xr-x 1 user 197121 0 Mar  2 14:52 .git/
drwxr-xr-x 1 user 197121 0 Mar  2 13:50 ejercicio1/

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ ls
ejercicio1/

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ git add .

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ git commit -m 'Versión Inicial'
[master (root-commit) 4b00243] Versión Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md

user@David-PC MINGW64 ~/desktop/ejercicios (master)
$ git log
commit 4b00243840f076115c0c0852fed018d76299ce5e (HEAD -> master)
Author: Paola <paolabricenov@outlook.com>
Date:   Thu Mar 2 15:00:58 2023 -0500

    Versión Inicial

user@David-PC MINGW64 ~/desktop/ejercicios (master)

Cambio.

user@David-PC MINGW64 ~/desktop/ejercicios/ejercicio1 (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text.txt

nothing added to commit but untracked files present (use "git add" to track)

user@David-PC MINGW64 ~/desktop/ejercicios/ejercicio1 (master)
$ git add .

user@David-PC MINGW64 ~/desktop/ejercicios/ejercicio1 (master)
$ git commit -m 'Agrega solución primer ejercicio'
[master a0e89dc] Agrega solución primer ejercicio
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/text.txt

user@David-PC MINGW64 ~/desktop/ejercicios/ejercicio1 (master)
$ git log
commit a0e89dc869ebbe4ec0a74390ecafa8dccbd07998 (HEAD -> master)
Author: Paola <paolabricenov@outlook.com>
Date:   Thu Mar 2 15:50:53 2023 -0500

    Agrega solución primer ejercicio

commit 4b00243840f076115c0c0852fed018d76299ce5e
Author: Paola <paolabricenov@outlook.com>
Date:   Thu Mar 2 15:00:58 2023 -0500

    Versión Inicial

user@David-PC MINGW64 ~/desktop/ejercicios/ejercicio1 (master)
$# aspirantes-mir-ejercicio-1
Ejercicio 1
