# Placed Operations

This Github organisation contains any code developed by the Placed Operations team! 🚀



To push local code here, first create a new repository with the name of your local repo, <Your Repo> (Note the repo should already be a git repo, e.g. run `git init`).
Run the following to add a remote called `placed` (you will have have setup `Github` access to your account on your machine):

```console
git remote add placed https://github.com/Placed-Operations/<Your Repo>.git
```

Run:
```console
git push -u placed master
```
To push to the master branch to the Github repo, note that you will first have to have added files and commited them to the local repo.
  
Now, whenever you make changes, commit them run:
```console
git push placed master
```
To update the Github repo!
