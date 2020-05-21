# A Million Monkeys Writing Shakespeare with Git
This repository is for teaching how to work with git.

In this repository, there are 300 pages to a book that hasn't been written. Follow along with the instructions to get into the workflow. It is highly recommended that you go over the terms in Atlassian's Git overview here: https://www.atlassian.com/git/tutorials/source-code-management

For Git, you need to know the following key terms: 
* Repository, or repo: the container for all the code that will be controlled and monitored by Git
* Branch: a different version of the repository that contains a series of changes that are grouped as a single set. A repository can have multiple branches. There is usually a Master Branch and a Development Branch
* Local: the version of the repository that exists on your machine. When used to describe branches, they are branches that are present and available on the machine.
* Remote: the version of the repository that exists online, this is its own set of branches entirely. Remote is not worked on directly.
* Clone: creating a local copy of the remote repository
* Commit: Telling git to save the changes that you have made to the file in the Git history. This is different than saving the file. Committing the changes allows git to track them.
* Merge: Combining a one branch's set of changes into another branch. e.g. You merge the Development branch into Master.
* Push: Sending the changes from the local repository to the remote repository.
* Pull: Updating the current local branch with changes from the remote version of the same branch.
* Conflict: Occurs when a branch's changes are incompatible with another branch's

With all of that in mind, you are ready to try this git activity and your own page to the book!

## Instructions
1. Clone this repo wih your preferred git client of choice
2. Switch to the 'development-writing' branch
3. Create a local branch off of the 'development-writing' with the name format 'Page-###-Writing' where ### is replaced with the page number. 001, 011, or 200
4. Open the page with that number you selected
5. Add your own amazing writing to that page
6. Save that document
7. Return to github and Commit your changes.
8. Merge your writing branch to the development branch.
9. Push the changes and make a pull request.
10. Wait for someone to approve that pull request
11. Congratulations! You have now successfully added some changes to the page.
