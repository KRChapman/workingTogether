

**0.**  Partner A creates a brand new repo in thier github with a readme.

**1.**  Fork Partner B forkes the newly created repo.

**2.**  Partner A clones their repo they created and Partner B clones the repo they forked.


**3.** Navigate to the project directory :file_folder: .

```
cd Blood-Buddy
```

**4.** Add a remote upstream to the original repository.

```
Partner B adds a remote with command: git remote add upstream https://github.comTHIS-SHOULD-BE PARTNER-A-REMOTE.git
```

**5.** Check the remotes for the repository.

```
git remote -v
```

**6.** It is always advised to take a pull from the upstream repository to your master branch to keep it even with the main project(updated repository).

```
git pull upstream  main(or master)
```

**7.** Both Parnters can Create a new branch with the name of the feature or page they are working on.

```
git checkout -b <your_branch_name>
```

**8.** Perform your desired changes to the code base.

<p align="center"><img width=35% src="https://media.giphy.com/media/oMHPlvpTvnXGPS7GhX/giphy.gif"></p>

**9.** Track your changes:heavy_check_mark: .

```
git add . 
```

**10.** Commit your changes .

```
git commit -m "Message related to changes you made in the code"
```

**11.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**12.** To create a pull request, click on `compare and pull requests`. Please ensure that both the branches are even in order to avoid merge conficts

**13.** Add a title and description to your PR explaining the features you added.

**14.** Click on `Create Pull Request`.

**15.** Congrats !! You made your first PR 🥳.

<p align="center"><img width=35% src="https://media.giphy.com/media/TdfyKrN7HGTIY/giphy.gif"></p>
<hr>

