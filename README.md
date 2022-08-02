


!!! Only do 0 through 4 once for setup !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Remember Partner A is the one person who has a main repo everyone else is Partner B.
<br>
<br>
**0.**  Partner A creates a brand new repo in their github (with a readmeif not using create-react-app).
<details><summary>Folow For React</summary>

1. In terminal type `npx create-react-app my-app-name-here`
2. In terminal type `cd my-app-name-here`
3. Go to github and create a new repository without a readme
4. Follow the directions github(skip commit and every thing before it) start at re-naming the branch from master to main

`git branch -M main`

`git remote add origin https://github.com/**YourURLHERE**/**YourREPO**t.git`   ( Copy and paste YOUR remote)

`git push -u origin main`

</details>

**1.**  Partner B forkes the newly created repo.

**2.**  Partner A If not using react clones their repo they created. Then Partner B clones the repo they forked regardles of what library they are using.


**3.** Navigate to the project directory :file_folder: .

```
cd <your project folder>
```

**4.** Partner B Add a remote upstream to the original repository created by partner A.
Partner B adds a remote with command:
```
 git remote add upstream https://github.com-Partner-A-Remote.git
```
Only do 0 through 4 once for setup!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

**5.** Check the remotes for the repository.

```
git remote -v
```

<br>
<br>

START HERE FOR EVERY PAGE OR FEATURE YOU MAKE!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
<br>


**6.** It is always advised to take a pull from the upstream repository to your main/master branch to keep it even with the main project(updated repository).

Make SURE you are in main when you pull
```
git checkout main(or master)
```
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
git checkout -b your_branch_name
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
git push -u origin your_branch_name
```

**12.** Go to your github To create a pull request, click on `compare and pull requests`.

**13.**  Add a title and description to your PR explaining the features you added.

**14.** Click on `Create Pull Request`.

**15.** Partner A will Accept the Pull Request and merge changes.

<p align="center"><img width=35% src="https://media.giphy.com/media/TdfyKrN7HGTIY/giphy.gif"></p>
<hr>

