-----------

<p align="center">

<img src="https://user-images.githubusercontent.com/40952801/177514419-ee33e903-8ef1-44a3-9a6a-6214595b78a6.png" alt="Placed Logo">
<h1 align="center">Placed Operations</h1>

</p>

-----------

This Github organisation contains any code developed by the Placed Operations team! 🚀


## Adding a Repo

To push a local `git`  repo to this remote, first create a new `GitHub` repository with the name of your local repo, `<your-repo>`.
Run the following to add a remote called `placed`:

```shell
git remote add placed https://github.com/Placed-Operations/<your-repo>.git
```

To push the local code to the Github repo, run:
```shell
git push -u placed master
```
Note that you will first have to add and commit files, as well as setup `GitHub` access to your account on your machine.


Now, whenever you make local changes, commit them and run:
```shell
git push placed master
```
This will update the (remote) `GitHub` repo with your local changes.

  
## Cloning a Repo
You can clone a repo by runnning the following `git` command:

```shell
git clone https://github.com/Placed-Operations/<repo-to-clone>.git
```

