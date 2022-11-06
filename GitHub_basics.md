# GitHub basics
GitHub - a code hosting platform for version control and collaboration (being online makes it easier to work with other people and orginize projects into portfolio)

## Resources
  [Git and GitHub for Beginners - Crash Course](https://youtu.be/RGOj5yH7evk)
  
  [GitHub get started](https://docs.github.com/en/get-started)

## Terms
  **CLI** - command line interface
  
  **Directory** - folder
  
  **Repository** - project, or folder/place where your project is kept.
  
  **Commits** - saved changes

## MD files
If you want to add a few text files like I did, you just press "New" and add .md to the name of your file.

They are written in the plain [Markdown language](https://www.markdownguide.org/cheat-sheet/).

For example:

    # Heading 1
    ## Heading 2
    ### Heading 3
    
    **bold text**
    *italicized text*
    ==highlight==
    `code`
    
    horizontal ruler: --- 
    link: [title](https://www.example.com)
    image: ![alt text](image.jpg)
    adding tabs will make a grey window like this one

## README.md
Readme.md is a project description with mockups. It's the default file that Github shows as a description.
    
Each repository should include a README.md file with information about your project (other people and employer can read it and quickly understand what your project is about and what knowledge do you have)
    
## A Repository
A repository is usually used to organize a single project (can contain folders and files, images, videos, spreadsheets, and data sets)

Create a repository:

	1. In the upper-right corner of any page, use the  drop-down menu, and select New repository.
	2. Enter repository name
	3. Add description
	4. select "add a README file"
	5. Select Public/private
	6. Create
![image](https://user-images.githubusercontent.com/64921934/200170971-cdb33f76-c231-4745-81b5-b86da942cec5.png)

## Branch
default branch is "main"
You can add aditional branches to have different versions of a project at one time.
The work done on different branches will not show up on the main branch until you merge it. You can use branches to experiment and make edits before commiting them to main

When you create a branch off the main, you make a copy as it was at that point in time.
![image](https://user-images.githubusercontent.com/64921934/200170992-9a20daa1-5a23-47f8-a6cc-1b2b7e989f9d.png)

This is like saving different versions of a file:

	story.txt
    
	story-edit.txt
    
	story-edit2.txt

Create a branch:

	1. Click "Code" tab of your repository
	2. Click the drop down at the top of the file list that says "main"
	3. Type a branch name and click "create branch: name-of-the-branch from main"

## Commits
A saved change.

Every commit has an associated commit message, which is a description explaining why a particular change was made.

## Opening a pull request
When you have changes in a branch off of main, you open a pull request to propose your changes, request someone's review, pull in your contribution and merge them into their branch.
It shows differences of content in different colors.
In the left upper corner you can see "commits" and see your history of changes:
    white - stayed the same
    -red - changed
    +green - new line

You can @mention a specific person.

	1. Click the Pull requests tab of your repository
	2. Click new request
	3. Check if this is what you want to submit
	4. Click create pull request
	5. Give it a title
	6. Optionally, to the right of your title and description, click the  next to Reviewers. Assignees, Labels, Projects, or Milestone to add any of these options to your pull request.
	7. Create pull request
Now your collaborators can review your edits and make suggestions

## Merging pull request
After you merge your pull request, the changes on your readme-edits branch will be incorporated into main
If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging until the conflicts are resolved.

	1. Merge pull request
	2. Confirm merge
	3. Delete readme-edit branch


GitHub's pull request workflow: write code -> commit changes -> if you don't own a repository or make it with other people + make a pull request
							

Files can be created locally on your machine or directly on a Github website
