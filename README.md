# Mager bin

My personal bin scripts.


## gitcleaner

Wizard that quickly lets you pick and choose which "untracked files" in your git status to delete.

Some background:

- git clean -n
    - lists the files "git clean -df" would delete

- git clean -df
    - deletes all files in the "untracked files" section of your git status

- If you want to delete all files listed by of "git clean -n", run "git clean -df"

- If you only want to delete SOME of the files listed by "git clean -n", use gitcleaner! 
It lets you easily pick and choose which untracked files to delete.


### gitcleaner usage:
~~~
$ cd my_git_repo
$ gitcleaner
Delete f1? [Yn]
Delete f2? [Yn] n
The following are queued for deresolution:
f1
Confirm deresolution? [Yn]
Files derezzed.
~~~

copyright (c) Rob Simmons 2017
