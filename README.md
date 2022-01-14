Code journal
01/13/2022
with first git bash activity i encountered some problems navigating to my file location, and after couple of failed attempts i was fortunate to collab with classmate, Maryam, and was able to navigate to specific file locations with her assistance.
Second activity was fun but annoying at the same time because i kept running into problems with git push, renaming the local master branch to main, and other technical difficulties. After struggling for some time trying to figure it out own my own, i reached out to Maryam and Hyeju for some clarity. Thanks to hyeju i was able to change branch from master to main. And i also would like to thank them both for helping me out with github and git bash.

some of the problems: 
17808@JIBRIL MINGW64 ~/documents/code-journal/my-repo (main)
$ git commit -m "add README to initial commit"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
17808@JIBRIL MINGW64 ~/documents/code-journal/my-repo (main)
$ git remote add origin https://github.com/jibril96/code-journal .git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


17808@JIBRIL MINGW64 ~/documents/code-journal/my-repo (main)
$ git push --set-upstream origin main
fatal: https://github.com/jibril96/Code-journal#code-journal.git/info/refs not valid: is this a git repository?

17808@JIBRIL MINGW64 ~/documents/code-journal/my-repo (main)
17808@JIBRIL MINGW64 ~/documents/code-journal (main)
$ git push --set-upstream origin main
To https://github.com/jibril96/code-journal
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/jibril96/code-journal'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.