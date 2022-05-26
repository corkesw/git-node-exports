# Repos

> ## Forking

- Making a copy of a repo in your own GitHub account. Changes to a forked repo will only exist in your forked copy
- This action is carried out on GitHub itself

> ## Cloning

- You will either be cloning the repo that you have just forked or one that another student has forked

```
git clone <paste link from github>
```

> ## Installing packages (or dependencies)

- most of the repos will already have a `package.json`
- check that it's there and then 

```
npm install
```

> ## Managing files

```
git add <filename>
```
 - adds a file to the staging area 
 - this is simply a list of files that will be added to a commit when we run:

```
git commit -m <add commit message here>
```

- once we have committed our changes locally, we can update GitHub using

```
git push origin main
```
