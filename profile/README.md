# Placed Operations

This Github organisation contains any code developed by the Placed Operations team! 🚀


## Adding a Repo

To push local code here, first create a new repository with the name of your local repo, <Your Repo> (Note the repo should already be a git repo, e.g. run `git init`).
Run the following to add a remote called `placed` (you will have have setup `Github` access to your account on your machine):

```console
git remote add placed https://github.com/Placed-Operations/<Your Repo>.git
```

To push the local code to the Github repo, run:
```console
git push -u placed master
```
Note that you will first have to add and commit files.

Now, whenever you make changes, commit them and run:
```console
git push placed master
```
This will update the (remote) Github repo with your local changes.

  
## Cloning a Repo
You can clone a repo by runnning the following `git` command:

```console
git clone https://github.com/Placed-Operations/<repo-to-clone>.git
```
