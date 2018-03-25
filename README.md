# project-newbs
This is a project intended to provided experience in collaborating in a development environment. We will be cloning a website using 3 technologies: HTML, CSS, and JavaScript. The group will be using the Agile Scrum methodology in building the site. 

# Working on Git

## Initial Set up

### Clone the repo:
 1. $ git clone < YOURTEAMREPO >
 2. $ git checkout develop
 3. $ git checkout -b < BRANCHNAME >
     - this creates the branch and immediately checks out the branch
     - see below for branch naming convention

> **Branch Naming Convention**
> - Branch names consists of 3 elements
>   - Issue type
>   - Feature Name
>   - Your Name
>
> **We'll have 4 issue types for now**
> - bug
> - feature
> - style
> - refactor
>
> **Feature Name**
> - Use camel case for feature names
>
> **Example**
> - git checkout -b feature-navigationBar-bobJones

# Working on your Branch

- Always do a git pull to make sure you are working on the latest code
- Always work on your branch
- Commit often 
	- make atomic commits 
	- this makes it easier to revert to an older version without losing a lot of work

### Steps to take when working on your Branch
1. $ git checkout development  
2. $ git pull origin development  
3. $ git checkout < BRANCHNAME >

### Pushing your Commits
1. $ git checkout development  
2. $ git pull origin development  
3. $ git checkout < BRANCHNAME >
4. $ git merge development  
5. $ git push origin < BRANCHNAME >

### Team Members
Aracely Valencia
Jon Mladia
Karren Zoleta
