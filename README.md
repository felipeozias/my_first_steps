# **_Questões da aula 06 (hard Skil)_**

1.
https://github.com/felipeozias/my_first_steps.git

2.
$ git init
Initialized empty Git repository in C:/Users/CIP/Desktop/primeiroDiretorio/.git/

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (master)
$ git branch -M "main"

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git remote add origin https://github.com/felipeozias/my_first_steps.git

3.
$ notepad ola_mundo.txt

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git status -s
?? ola_mundo.txt

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git add .

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git status -s
A  ola_mundo.txt

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git commit -m "Commit inicial"
[main (root-commit) c344901] Commit inicial
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/felipeozias/my_first_steps.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

4.
$ touch .gitignore

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ notepad serei_ignorado.txt

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git status -s
?? .gitignore
?? serei_ignorado.txt

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ echo serei_ignorado.txt >> .gitignore

CIP@DESKTOP-442L2NV MINGW64 ~/Desktop/primeiroDiretorio (main)
$ git status -s
?? .gitignore

