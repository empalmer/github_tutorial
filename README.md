# github_tutorial
A github tutorial for fellow PhD Students at Oregon State University


## Forking an existing repository: 

Forking: Make a copy of someone's public github repository to your own account.


- Fork this repository! 
- Clone the repository to your local machine: 
Find the green "<> Code" button, and copy the URL 
This will copy the repository to your local machine. 

Open R Studio, 
File, New Project, Version Control, Git, paste the URL in the "Repository URL" box.

You now have a local copy of the repository on your machine.

### Make some changes!

Write somethign here, or correct my typo!
Save file 

### Version control: How/why
You've made a change. Now you want to confirm you made a change, document that you have made a change, and save the change remotely. 

Confirm you made a change: Git add 
- Adds the saved version of the file to the staging area
Document you made a change: Git commit
- Commits the changes locally with a description of what you did
Save the change remotely: Git push
- Pushes the changes to the remote repository


#### Option 1: Use R Studio's git interface
- Go to the Git tab in the upper right hand corner of R Studio
- Check the box next to the file you want to commit
- Write a commit message in the box at the top of the Git tab
- Click "Commit"
- Click "Push" to push the changes to the remote repository


#### Option 2: Command line 
- Open a terminal
- Navigate to the repository
- `git add .`
- `git commit -m "Your message here"`
- `git push`


### Overview: 
- Add and commit are local 
- Push and pull are to Github 

## Branches: How you are supposed to use Git/Github (but I dont always tbh)
What are branches for?
- Main branch: Stuff you know works
- Branches: Stuff you are working on, but don't want to mess up what you know already works 
- Branches are a way to work on a project with other people without conflicting


- Create a new branch:
`git checkout -b new_branch_name`
- Make some changes
- Commit the changes 

- Push the branch to the remote repository
`git push --set-upstream origin branch_test`

- View the differences on GitHub and if you like the changes, merge the branches
- Create a pull request 
- Merge the branch to the main branch


## Keep track of what you have done
- Commit messages and Diff files!
- Commit messages should be informative and concise
- Diff files show what you have changed in a file
- Use these tools to keep track of what you have done and why you have done it




## Branches: How you are supposed to use Git/Github (but I dont always...)
What are branches for? 
- Branches are a way to work on a project without affecting the main branch
- Branches are a way to work on a project with other people without affecting the main branch
- Main branch: Stuff you know works
- Branches: Stuff you are working on, but don't want to mess up what you know already works 



- Create a new branch:
`git checkout -b new_branch_name`
- Make some changes
- Commit the changes
- Push the changes to the remote repository
- Create a pull request to merge the changes into the main branch
- Merge the changes into the main branch


## Review what you have done

On github, check out the commits 


## Make your own repository: 

Students get free github education, which includes the ability to have private repositories (and github copilot). 

Good things to do: 
- Add a README.md file
- Decide on private/public
- Add a .gitignore file, using the R settings
- Add a license 



## Resources: 
A great 
https://docs.github.com/en/get-started/start-your-journey/hello-world