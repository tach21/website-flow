# website-flow

List of favorite pizzas! 

-pepperoni
-honestly anything that doesn't have any pinapple on it. 


terminal control!
-->
Degiovannis-MBP:WCS Tach$ git clone git@github.com:tach21/website-flow.git
Cloning into 'website-flow'...
Enter passphrase for key '/Users/Tach/.ssh/id_rsa':
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
Degiovannis-MBP:WCS Tach$ cd website-flow/
Degiovannis-MBP:website-flow Tach$ code .
Degiovannis-MBP:website-flow Tach$ ls
README.md
Degiovannis-MBP:website-flow Tach$ git checkout -b cheese
Switched to a new branch 'cheese'
Degiovannis-MBP:website-flow Tach$ git status
On branch cheese
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Degiovannis-MBP:website-flow Tach$ git add README.md
Degiovannis-MBP:website-flow Tach$ git commit -m "Pizza"
[cheese e04a40c] Pizza
 1 file changed, 6 insertions(+), 1 deletion(-)
Degiovannis-MBP:website-flow Tach$ git status
On branch cheese
nothing to commit, working tree clean
Degiovannis-MBP:website-flow Tach$ git push origin "cheese branch"
fatal: invalid refspec 'cheese branch'
Degiovannis-MBP:website-flow Tach$ git push origin
fatal: The current branch cheese has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin cheese

Degiovannis-MBP:website-flow Tach$ git push origin cheese
Enter passphrase for key '/Users/Tach/.ssh/id_rsa':
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 335 bytes | 335.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'cheese' on GitHub by visiting:
remote:      https://github.com/tach21/website-flow/pull/new/cheese
remote:
To github.com:tach21/website-flow.git
 * [new branch]      cheese -> cheese
Degiovannis-MBP:website-flow Tach$ git status
On branch cheese
nothing to commit, working tree clean
Degiovannis-MBP:website-flow Tach$ git branch -d cheese
error: Cannot delete branch 'cheese' checked out at '/Users/Tach/Desktop/WCS/website-flow'
Degiovannis-MBP:website-flow Tach$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
Degiovannis-MBP:website-flow Tach$ git branch -D cheese
Deleted branch cheese (was e04a40c).
Degiovannis-MBP:website-flow Tach$ git branch
* master
<----
