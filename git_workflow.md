Git Steps:
1) Start on local master
2) Git pull origin master to make sure your local master is completely up to date
3) Git checkout -b new-branch-name (remember, the name should be a short description of what you're planning to do in this branch) to create and check out your new branch.
4) Do some work. Make commits along the way.
5) When your work is fully functional and well-tested, push your local branch up so that you create a remote version of that branch
6) Go to that remote branch on github
7) Put in a pull request for that remote branch into your remote master
8) Ideally someone else would review your code and merge your pull request into master (but if you're working on an independent project, you'll do this yourself)
Now, remote master has all the hard work you've done! However, your local master does not. So, to get the updates from remote master and continue working, you'd start over from step 1 all over again.
..


Hello World!
How are you?

I just created a branch with git checkout -b name_of_branch
