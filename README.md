

**0.**  Partner A creates a brand new repo in their github with a readme.

**1.**  Partner B forkes the newly created repo.

**2.**  Partner A clones their repo they created and Partner B clones the repo they forked.


**3.** Navigate to the project directory :file_folder: .

```
cd <your project folder>
```

**4.** Partner B Add a remote upstream to the original repository created by partner A.
Partner B adds a remote with command:
```
 git remote add upstream <<<<https://github.comTHIS-SHOULD-BE PARTNER-A-REMOTE.git>>>>>>
```

**5.** Check the remotes for the repository.

```
git remote -v
```

<br>
<br>
<br>

START HERE FOR EVERY PAGE OR FEATURE YOU MAKE


**6.** It is always advised to take a pull from the upstream repository to your main/master branch to keep it even with the main project(updated repository).

Make SURE you are in main when you pull

Partner A
```
git pull origin main(or master)
```

Partner B
```
git pull upstream main(or master)
```

**7.** Both Parnters can Create a new branch with the name of the feature or page they are working on.
 Make sure you are on main or master and type git status and that it is working and clean.
```
git status 
git checkout -b <your_branch_name>
```

**8.** Perform your desired changes to the code base.

<p align="center"><img width=35% src="https://media.giphy.com/media/oMHPlvpTvnXGPS7GhX/giphy.gif"></p>

**9.** Track your changes:heavy_check_mark: .

```
git add -A 

```
or
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

**12.** To create a pull request, click on `compare and pull requests`.

**13.**  Add a title and description to your PR explaining the features you added.

**14.** Click on `Create Pull Request`.

**15.** Partner A will Accept the Pull Request and merge changes.

<p align="center"><img width=35% src="https://media.giphy.com/media/TdfyKrN7HGTIY/giphy.gif"></p>
<hr>

