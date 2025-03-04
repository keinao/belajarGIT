Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
jeann@LAPTOP-5RD3EO7R MINGW64 ~
$ cd Documents

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents
$ git clone https://github.com/keinao/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents
$ cd belajarGIT

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 6883b9b] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 3181132..6883b9b
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/keinao/belajarGIT.git
   3181132..6883b9b  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 8ae6d7e] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 6883b9b..8ae6d7e
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/keinao/belajarGIT.git
   6883b9b..8ae6d7e  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css c8aab0a] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 8ae6d7e..c8aab0a
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 367 bytes | 367.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/keinao/belajarGIT.git
   8ae6d7e..c8aab0a  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js f2169ef] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating c8aab0a..f2169ef
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keinao/belajarGIT.git
   c8aab0a..f2169ef  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject e9d2a71] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating f2169ef..e9d2a71
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keinao/belajarGIT.git
   f2169ef..e9d2a71  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 78b1e37] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating e9d2a71..78b1e37
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keinao/belajarGIT.git
   e9d2a71..78b1e37  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject ef92800] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 78b1e37..ef92800
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keinao/belajarGIT.git
   78b1e37..ef92800  main -> main

jeann@LAPTOP-5RD3EO7R MINGW64 ~/Documents/belajarGIT (main)
$
