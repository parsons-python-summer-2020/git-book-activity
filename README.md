# A Million Monkeys Writing Shakespeare with Git
This repository is for teaching how to work with git.

In this repository, there are 300 pages to a book that hasn't been written. Follow along with the instructions to get into the workflow.

## Instructions
1. Clone this repo wih your preferred git client of choice
2. Switch to the 'development-writing' branch
3. Create a local branch off of the 'development-writing' with the name format 'Page-###-Writing' where ### is replaced with the page number. 001, 011, or 200
4. Open the page with that number you selected
5. Add your own amazing writing to that page
6. Save that document
7. Return to github and commit your changes.
8. Merge your writing branch to the development branch.
9. Push the changes and make a pull request.
10. Wait for someone to approve that pull request
11. Congratulations! You have now successfully added some changes to the page.

### What has happened:
By submitting your pull request, you have asked to contribute to a branch's history. This lets the owner of the project review the changes and approve them before combining them into the rest of the project. Here is here conflicts can be managed and fixed if need be. 

Even once the pull request is made, all changes are not immediately made available. By choosing which branch to merge your changes into, git can keep a master branch clean from pull requests and allow the development branch to take most of the changes. This keeps the history of the master branch tidy, as it will only ever contain merges from the development branch. 

Once the development branch is merged into the master, then the rest of the changes that we collectively worked on in the development branch will be available to see in the master branch.

Feel free to continue to play with any of the pages or make new branches off of the development branch as you need to. The pull requests will be managed for the duration of the class.
