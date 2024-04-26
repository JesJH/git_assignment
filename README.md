# Git Assignment - JesJH
a. What is an issue?
Issue is an item you can create in a repository to plan, discuss and track work and is used
to communicate with others.
 
b. What is a pull request?
Pull request is a proposal to merge a set of changes from one branch to another.
It allows collaborators to review and discuss proposed set of changes before integrating to
main codebase.

c. How do I open up a pull request?
On the Github website, go to the main repository. From the branch menu, select the branch
that contains the commits you are trying to review. Click on the button at the top that says
"Compare & pull request" to compare what changes have been made in the request.

d. Give me a step by step guide on how to add someone to your repository.
On Github.com, go to the repository you want to give collaborators access to. Click on
'Settings' right next to the 'Insights' button. This takes you to a new page. On the left
side of the page, under 'Access', click on 'Collaborators'.This will prompt you to type in
your Github password. After entering your password, click on 'Add People' and add collaborators
to your repository using either their email address, full name or Github username.


e. What is the difference between git and GitHub?
Git is an open source software maintained by Linux. Github is owned and operated by Microsoft
and is an online platform and service for managing code using Git.

f. What does git diff do?
git diff is a git command to display differences between the working directory and the lat commit.

g. What is the main branch?
The main branch is the default branch of a repository and is considered the 'master' location where
only code that is tested and can be pushed to production should be stored. When working on new
features, you'd most likely start by taking a copy of the main branch and then work on the 
changes locally.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
It is not recommended to push directly to the main branch, especially if you are working with others. It is best practice
for each new feature to have its own branch and changes being committed to its own feature branch. This practice
also supports code review processes, makes it easier for collaboration and testing because testing can be done in isolation.
