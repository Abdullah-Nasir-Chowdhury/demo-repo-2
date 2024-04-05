# Demo 2

Some text

To turn it into a github repository, go into the cmd line interface and type `git init`
</br>You will see this message in the terminal: 

`Initialized empty Git repository in C:/Users/HP/Desktop/My Papers/Conferences/Bangla OCR/Code/demo-repo-2/.git/`

Use `git status` to see the untracked files
`git add` to add it
`git commit -m [message]` to commit it
now if you use `git push origin main` it wont be able to do that, because, it's not a clone. we created it locally.
You can do 2 things:
1. Create a new repo on github with the same name as your folder: demo-repo-2
2. Use `git remote add origin [ssh_protected_link_that_you_copied]