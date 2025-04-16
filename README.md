# PART 2: Simulating Tom and Jerry's Work
## `This guide will walk you through the basics of using GitHub, including navigating a project directory, creating branches, making changes, and collaborating with others. We'll simulate workflows for two contributors, Tom and Jerry` 

# Navigating the Project Directory and Checking Branches:
## Steps:

1. Navigate to the project directory you just cloned using the command:
``` bash
cd ai-startup-website
```
2. ### Check the current branch in repository using:
``` bash
git branch
```
This will display all the branches in the repository.

3. ### Create a new branch called `update-navigation`
``` bash 
git branch update-navigation
```
4. ### Verify the new branch by running git branch again. You should see the newly created branch listed.

![git](./image/git-Navigating.PNG)

# Making Changes and Staging Them
## Steps:

1. ### Open the index.html file in your code editor. Since this file already exists in the main branch, it will also exist in the new branch you created.

2. ### Add the following content to the index.html file:

``` bash
This is Tom adding Navigation to the ai-startup-website
```
![vi](./image/vi.png)

3. ### Check the status of your changes using:
``` bash
git status
```
This will show that the change has not been staged yet.
Staging the change using `git add .`

![staging](./image/staging-status.PNG)

# Committing and Pushing Changes.

Steps:

1. ### Commit the change with a message.

``` bash 
git commit -m "update the navigation bar"
```
![commit-push](./image/add-commit.png)

2. ### Push the branch to GitHub using:

``` bash 
git push origin main
```

![git-push](./image/git%20push.png)

# Simulating Jerry's Contribution:
Steps:

1. ### Switch back to the update-navigation branch:
``` bash
git checkout update-navigation
```





