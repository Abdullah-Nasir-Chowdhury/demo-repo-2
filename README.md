# Demo 2

Some text

To turn it into a github repository, go into the cmd line interface and type `git init`
</br>You will see this message in the terminal: 

`Initialized empty Git repository in C:/Users/HP/Desktop/My Papers/Conferences/Bangla OCR/Code/demo-repo-2/.git/`

Use `git status` to see the untracked files
`git add` to add it
`git commit -m [message]` to commit it
now if you use `git push origin main` it wont be able to do that, because, it's not a clone. we created it locally.
You can do it by the following steps:
1. Create a new repo on github with the same name as your folder: demo-repo-2
2. Use `git remote add origin [ssh_protected_link_that_you_copied]`
3. Check that using `git remote -v`
4. Now use `git branch --list` to see whether or not you have a main or master branch
5. Use `git push origin main` or `git push origin master` to push it to the appropriate branch
6. Use `git status` to see the untracked and modified files.
7. Use `git add .` to add all the untracked files
8. Use `git commit -m ["message"]` to commit to push
9. Use `git push origin master` to push to master branch
10. to not use the long `git push origin master` you can create an upstream `git push -u origin master` meaning this is where I want to push by default. Now I can use `git push` only without typing in origin master in the future
