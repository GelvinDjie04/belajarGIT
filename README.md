Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
Gaelv@Vinn MINGW64 ~
$ cd C:\PemrogramanWeb

Gaelv@Vinn MINGW64 /c/PemrogramanWeb
$ cd https://github.com/GelvinDjie04/belajarGIT.git
bash: cd: https://github.com/GelvinDjie04/belajarGIT.git: No such file or directory

Gaelv@Vinn MINGW64 /c/PemrogramanWeb
$ https://github.com/GelvinDjie04/belajarGIT.git
bash: https://github.com/GelvinDjie04/belajarGIT.git: No such file or directory

Gaelv@Vinn MINGW64 /c/PemrogramanWeb
$ git clone https://github.com/GelvinDjie04/belajarGIT.git
\Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb
$ cd belajarGIT

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-git)
$ git commit -m "add Tugas-Git.txt"
[Tugas-git f69f9ce] add Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-git)
$ git commit -"Menambahkan Tugas-Git.txt
> "
error: unknown switch `M'
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u<mode>] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>)]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

    -q, --[no-]quiet      suppress summary after successful commit
    -v, --[no-]verbose    show diff in commit message template

Commit message options
    -F, --[no-]file <file>
                          read message from file
    --[no-]author <author>
                          override author for commit
    --[no-]date <date>    override date for commit
    -m, --[no-]message <message>
                          commit message
    -c, --[no-]reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --[no-]reuse-message <commit>
                          reuse message from specified commit
    --[no-]fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --[no-]squash <commit>
                          use autosquash formatted message to squash specified commit
    --[no-]reset-author   the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --[no-]signoff    add a Signed-off-by trailer
    -t, --[no-]template <file>
                          use specified template file
    -e, --[no-]edit       force edit of commit
    --[no-]cleanup <mode> how to strip spaces and #comments from message
    --[no-]status         include status in commit message template
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --[no-]all        commit all changed files
    -i, --[no-]include    add specified files to index for commit
    --[no-]interactive    interactively add files
    -p, --[no-]patch      interactively add changes
    -o, --[no-]only       commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --verify              opposite of --no-verify
    --[no-]dry-run        show what would be committed
    --[no-]short          show status concisely
    --[no-]branch         show branch information
    --[no-]ahead-behind   compute full ahead/behind values
    --[no-]porcelain      machine-readable output
    --[no-]long           show status in long format (default)
    -z, --[no-]null       terminate entries with NUL
    --[no-]amend          amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    --post-rewrite        opposite of --no-post-rewrite
    -u, --[no-]untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-git
Updating c644849..f69f9ce
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/GelvinDjie04/belajarGIT.git
   c644849..f69f9ce  main -> main

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-html)
$ git add -m "add Tugas-html.txt"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --[no-]dry-run    dry run
    -v, --[no-]verbose    be verbose

    -i, --[no-]interactive
                          interactive picking
    -p, --[no-]patch      select hunks interactively
    -e, --[no-]edit       edit current diff and apply
    -f, --[no-]force      allow adding otherwise ignored files
    -u, --[no-]update     update tracked files
    --[no-]renormalize    renormalize EOL of tracked files (implies -u)
    -N, --[no-]intent-to-add
                          record only the fact that the path will be added later
    -A, --[no-]all        add changes from all tracked and untracked files
    --[no-]ignore-removal ignore paths removed in the working tree (same as --no-all)
    --[no-]refresh        don't add, only refresh the index
    --[no-]ignore-errors  just skip files which cannot be added because of errors
    --[no-]ignore-missing check if - even missing - files are ignored in dry run
    --[no-]sparse         allow updating entries outside of the sparse-checkout cone
    --[no-]chmod (+|-)x   override the executable bit of the listed files
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-html)
$ git add -m "add Tugas-html.txt"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --[no-]dry-run    dry run
    -v, --[no-]verbose    be verbose

    -i, --[no-]interactive
                          interactive picking
    -p, --[no-]patch      select hunks interactively
    -e, --[no-]edit       edit current diff and apply
    -f, --[no-]force      allow adding otherwise ignored files
    -u, --[no-]update     update tracked files
    --[no-]renormalize    renormalize EOL of tracked files (implies -u)
    -N, --[no-]intent-to-add
                          record only the fact that the path will be added later
    -A, --[no-]all        add changes from all tracked and untracked files
    --[no-]ignore-removal ignore paths removed in the working tree (same as --no-all)
    --[no-]refresh        don't add, only refresh the index
    --[no-]ignore-errors  just skip files which cannot be added because of errors
    --[no-]ignore-missing check if - even missing - files are ignored in dry run
    --[no-]sparse         allow updating entries outside of the sparse-checkout cone
    --[no-]chmod (+|-)x   override the executable bit of the listed files
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-html)
$ git commit -m "add Tugas-html.txt"
[Tugas-html 819bbf6] add Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-html
Updating f69f9ce..819bbf6
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/GelvinDjie04/belajarGIT.git
   f69f9ce..819bbf6  main -> main

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-css)
$ git commit -m "add Tugas-css.txt"
[Tugas-css ab3a2d7] add Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-css
Updating 819bbf6..ab3a2d7
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 284 bytes | 284.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GelvinDjie04/belajarGIT.git
   819bbf6..ab3a2d7  main -> main

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-js)
$ touch Tugas-js

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-js)
$ git commit -m "Tugas-js.txt"
[Tugas-js 8b9d173] Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-js
Updating ab3a2d7..8b9d173
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GelvinDjie04/belajarGIT.git
   ab3a2d7..8b9d173  main -> main

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-midProject.txt"
[Tugas-midProject fa12bf8] Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-midProject
Updating 8b9d173..fa12bf8
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 315 bytes | 315.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GelvinDjie04/belajarGIT.git
   8b9d173..fa12bf8  main -> main

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-php)
$ git commit -m "Tugas-php.txt"
[Tugas-php 8f7bb32] Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-php
Updating fa12bf8..8f7bb32
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GelvinDjie04/belajarGIT.git
   fa12bf8..8f7bb32  main -> main

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-finalProject)
$ git commit -m "Tugas-finalProject.txt"
[Tugas-finalProject fc15d81] Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 8f7bb32..fc15d81
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Gaelv@Vinn MINGW64 /c/PemrogramanWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GelvinDjie04/belajarGIT.git
   8f7bb32..fc15d81  main -> main
