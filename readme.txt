git is a distributed version control system
git is a free software under the GPL
git has a mutable index called stage
git tracks changes of files
creating a branch is quick AND simple
this is 3

learn how to use branch

commands:

git config --global user.name jingli
git config --global user.email jing.li@anl.gov

git add file1 [file2 ...]
git commit -m "instrcutions of modification"

git status // check which file(s) has been modified since last commit
git diff file // compare file difference between current and last commit
git diff HEAD -- file // comprae file difference between HEAD and current file
git diff HEAD^ HEAD^^ -- file // compare file difference between HEAD^ and HEAD^^
git log // list all commit forward
git reflog // list all log history(include backward)

git reset --hard HEAD^ // HEAD^ last commit HEAD^^ the one befor last HEAD~100
git reset --hard (commit number) // only the first few digits are enough
git reset HEAD file // unstage current stage for file
git checkout -- file // discard changes in working area, relative to the stage area or the last commit (back to last add or last commit)
