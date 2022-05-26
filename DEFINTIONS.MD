# Definitions

> ## Repository

- Also called a repo for short
 - A collection of files and each file's revision history

> ## Git and GitHub

- Git is a version control system that lets you manage and keep track of your source code history.
- GitHub is a cloud-based hosting service that lets you manage Git repositories

> ## Node.js

- Node.js is what allows us to run javascript locally on our machines.
- `node` is also a command used to run a javascript file
- the command below, when typed at the command line, will run the file index.js 

```
node index.js
```

- note that argument after node is the **filepath**
- if our working directory is not the same as the one where the file is located, we must also provide the **relative** filepath
- relative means relative our current working directory
- for example, if the file was located in a sub-directory called components:

```
node components/index.js
```

> ## npm

- or **Node Package Manager** – is the default package manager for node
- packages are collections of files that other developer have written and which we can incorporate in our projects
- the command `npm install`, followed by the name of a package, can be used to add packages to our projects
- the command `npm init` can be used to create a `package.json` file

> ## package.json
- this is a file which holds information about our project including which packages we have installed
- when we clone a repo down, we can add all of the packages that it uses by simply typing `npm install`
