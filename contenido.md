# GIT
##  Comandos para bitbucket
### Ver cambios en el repositorio
```git
git status
```
### Agregar cambios
```git
git add datos.txt
```
### Confirmar cambios
```git
 git commit -m 'nuevo txt'
```
### Agregar Origen
```git
git remote add origin https://github.com/rxfxngel/safepass.git
```
### publicar cambios en la nube
```git
git push -u origin master
```

#Ejemplo de ejecucion

```git
POWERBI@DESKTOP-2UMC58O MINGW64 ~/Documents/POWERBI_FRONTEND (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Balance and Report.pbix
        modified:   Batching.pbix
        modified:   Billing Managers.pbix
        modified:   Credentialing.pbix
        modified:   Customer Services.pbix
        modified:   Data Entry.pbix
        modified:   Follow Up.pbix
        modified:   MC.pbix
        modified:   Missing Information.pbix
        modified:   Notifies.pbix
        modified:   Operaciones - General.pbix
        modified:   Submission.pbix

no changes added to commit (use "git add" and/or "git commit -a")

POWERBI@DESKTOP-2UMC58O MINGW64 ~/Documents/POWERBI_FRONTEND (master)
$ git add .

POWERBI@DESKTOP-2UMC58O MINGW64 ~/Documents/POWERBI_FRONTEND (master)
$ git commit -m "Cambios de año mes"
[master 0da635e] Cambios de a├▒o mes
 12 files changed, 0 insertions(+), 0 deletions(-)
 rewrite Customer Services.pbix (82%)
 rewrite Follow Up.pbix (63%)
 rewrite Submission.pbix (61%)

POWERBI@DESKTOP-2UMC58O MINGW64 ~/Documents/POWERBI_FRONTEND (master)
$ git push
Enumerating objects: 27, done.
Counting objects: 100% (27/27), done.
Delta compression using up to 8 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (14/14), 7.62 MiB | 7.85 MiB/s, done.
Total 14 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Analyzing objects... (14/14) (2950 ms)
remote: Storing packfile... done (246 ms)
remote: Storing index... done (30 ms)
To https://codisoti.visualstudio.com/POWERBI_FRONTEND/_git/POWERBI_FRONTEND
   83b0cd3..0da635e  master -> master

POWERBI@DESKTOP-2UMC58O MINGW64 ~/Documents/POWERBI_FRONTEND (master)
$
```
