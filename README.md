# belajarGIT

Daftar tugas / branch
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah GiT
...

luke@Lukes-MacBook-Pro desktop % mkdir TIK2032-WebProgramming
luke@Lukes-MacBook-Pro desktop % cd TIK2032-WebProgramming 
luke@Lukes-MacBook-Pro TIK2032-WebProgramming % ls
luke@Lukes-MacBook-Pro TIK2032-WebProgramming % git clone git@github.com:lukemawuntu/belajarGIT.git
Cloning into 'belajarGIT'...
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
luke@Lukes-MacBook-Pro TIK2032-WebProgramming % ls
belajarGIT
luke@Lukes-MacBook-Pro TIK2032-WebProgramming % cd belajarGIT
luke@Lukes-MacBook-Pro belajarGIT % ls
README.md
luke@Lukes-MacBook-Pro belajarGIT % touch README.md 
luke@Lukes-MacBook-Pro belajarGIT % ls
README.md
luke@Lukes-MacBook-Pro belajarGIT % open README.md 
luke@Lukes-MacBook-Pro belajarGIT % open . 
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-git
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-git 
Switched to branch 'Tugas-git'
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch Tugas-git
nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-Git.txt
luke@Lukes-MacBook-Pro belajarGIT % open Tugas-Git.txt 
luke@Lukes-MacBook-Pro belajarGIT % open
Usage: open [-e] [-t] [-f] [-W] [-R] [-n] [-g] [-h] [-s <partial SDK name>][-b <bundle identifier>] [-a <application>] [-u URL] [filenames] [--args arguments]
Help: Open opens files from a shell.
      By default, opens each file using the default application for that file.  
      If the file is in the form of a URL, the file will be opened as a URL.
Options: 
      -a                    Opens with the specified application.
      --arch ARCH           Open with the given cpu architecture type and subtype.
      -b                    Opens with the specified application bundle identifier.
      -e                    Opens with TextEdit.
      -t                    Opens with default text editor.
      -f                    Reads input from standard input and opens with TextEdit.
      -F  --fresh           Launches the app fresh, that is, without restoring windows. Saved persistent state is lost, excluding Untitled documents.
      -R, --reveal          Selects in the Finder instead of opening.
      -W, --wait-apps       Blocks until the used applications are closed (even if they were already running).
          --args            All remaining arguments are passed in argv to the application's main() function instead of opened.
      -n, --new             Open a new instance of the application even if one is already running.
      -j, --hide            Launches the app hidden.
      -g, --background      Does not bring the application to the foreground.
      -h, --header          Searches header file locations for headers matching the given filenames, and opens them.
      -s                    For -h, the SDK to use; if supplied, only SDKs whose names contain the argument value are searched.
                            Otherwise the highest versioned SDK in each platform is used.
      -u, --url URL         Open this URL, even if it matches exactly a filepath
      -i, --stdin  PATH     Launches the application with stdin connected to PATH; defaults to /dev/null
      -o, --stdout PATH     Launches the application with /dev/stdout connected to PATH; 
          --stderr PATH     Launches the application with /dev/stderr connected to PATH to
          --env    VAR      Add an enviroment variable to the launched process, where VAR is formatted AAA=foo or just AAA for a null string value.
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)
luke@Lukes-MacBook-Pro belajarGIT % git add Tugas-Git.txt
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   Tugas-Git.txt

luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-Git.txt"
[Tugas-git 94fa2c1] Add file Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-git 
Updating 6593bf6..94fa2c1
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt
luke@Lukes-MacBook-Pro belajarGIT % git push       
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:lukemawuntu/belajarGIT.git
   6593bf6..94fa2c1  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-html               
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-html           
Switched to branch 'Tugas-html'
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch Tugas-html
nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-html.txt
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git add .
luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-html.txt"
[Tugas-html d2a9a29] Add file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-html 
Updating 94fa2c1..d2a9a29
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git push origin main
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 382 bytes | 382.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:lukemawuntu/belajarGIT.git
   94fa2c1..d2a9a29  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-css
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-css
Switched to branch 'Tugas-css'
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-css.txt
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git add .
luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-css.txt"
[Tugas-css 2c762a0] Add file Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-css
Updating d2a9a29..2c762a0
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt
luke@Lukes-MacBook-Pro belajarGIT % git push origin main
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:lukemawuntu/belajarGIT.git
   d2a9a29..2c762a0  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git push origin main
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Everything up-to-date
luke@Lukes-MacBook-Pro belajarGIT % git push origin main
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Everything up-to-date
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-css
fatal: a branch named 'Tugas-css' already exists
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-js
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-js
Switched to branch 'Tugas-js'
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-js.txt
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git add .
luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-js.txt"
[Tugas-js e8cf507] Add file Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-js    
Updating 2c762a0..e8cf507
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git push
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:lukemawuntu/belajarGIT.git
   2c762a0..e8cf507  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-midProject
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-midProject.txt
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git add .
luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-midProject.txt"
[Tugas-midProject 58f866c] Add file Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-midProject 
Updating e8cf507..58f866c
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt
luke@Lukes-MacBook-Pro belajarGIT % git push
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:lukemawuntu/belajarGIT.git
   e8cf507..58f866c  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-php
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-php
Switched to branch 'Tugas-php'
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-php.txt
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git add .
luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-php.txt"
[Tugas-php b89f664] Add file Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-php
Updating 58f866c..b89f664
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt
luke@Lukes-MacBook-Pro belajarGIT % git push
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 344 bytes | 344.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:lukemawuntu/belajarGIT.git
   58f866c..b89f664  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git branch Tugas-finalProject
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-finalProject 
Switched to branch 'Tugas-finalProject'
luke@Lukes-MacBook-Pro belajarGIT % touch Tugas-finalProject.txt
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % git add .
luke@Lukes-MacBook-Pro belajarGIT % git commit -m "Add file Tugas-finalProject.txt"
[Tugas-finalProject 13ec77d] Add file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git merge Tugas-finalProject
Updating b89f664..13ec77d
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git push
Enter passphrase for key '/Users/luke/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 359 bytes | 359.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:lukemawuntu/belajarGIT.git
   b89f664..13ec77d  main -> main
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git checkout Tugas-css 
Switched to branch 'Tugas-css'
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch Tugas-css
nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
luke@Lukes-MacBook-Pro belajarGIT % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
luke@Lukes-MacBook-Pro belajarGIT % code .
luke@Lukes-MacBook-Pro belajarGIT % 
