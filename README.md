# A03

### *GITHUB TUTORIAL*

1. Download and install JetBrains Webstorm from https://www.jetbrains.com/student/
2. Download and instal Git as a local program from https://git-scm.com/downloads
3. Create a GitHub account on https://github.com/join
4. Connect GitHub with Webstorm   
    4a) In Webstorm press (Ctrl+Alt+S) for system preferences   
    4b) Select Version control Git. Enter the path to the git.exe
5. Add GitHub password to Webstorm   
    5a) In Webstorm press (Ctrl+Alt+S) for system preferences   
    5b) SelectAppearance and Behavior | System Settings | Passwords
6. Create a repository on GitHub   
    6a) Click the + sign in the upper right corner   
    6b) Choose “Create New repository”
7. Set up the repository on GitHub   
    7a) Make the repository public and add the readme file   
    7b) Click "Create"
8. Create a repository on Webstorm   
    8a) Select VCS and Import into Version Control
9. Import a repository on GitHub   
    9a) From Main page Select Checkout from version control -> Git  OR  From within Webstorm Select VCS -> Checkout from version control -> Git   
    9b) Enter Github repository name   
    9c) Enter local path name
10. Create a Webstorm File   
    10a) Choose File -> HTML -> HTML 5 or File -> Stylesheet
11. Add files to Git on Webstorm   
    11a) The Add to Git dialog opens. Click Add. This adds to local file system
12. Click "Commit" to save changes on Webstorm
13. Click "Push" to save change to remote repository on GitHub   
    13a) Press “Ctrl + Shift + K” OR Click “VCS -> Git -> Push”
14. Check GitHub to confirm the pushed file is updated in the repository
15. Set up GitHub pages   
    15a) Click Settings and check the repository name
16. Choose GitHub page location   
    16a) Select “master branch” under "Source"   
    16b) Note the published URL
17. Test your GitHub pages to see if they work   
    17a) Copy the Github.io URL into a browser and press Enter
    
    
---
### *REFERENCES*
(IntroToGitHub-20190318.pptx)   
Hendela, A. (2019, March 18). Intro To GitHub. Retrieved September 28, 2020, from https://njit.instructure.com/courses/13292/files/folder/Week03?preview=984370


---
### *GLOSSARY*

•	**Branch** - A branch represents an independent line of development. Branches serve as an abstraction for the edit/stage/commit process.

•	**Clone** - Cloning is a process of creating an identical copy of a Git Remote Repository to the local machine.

•	**Commit** - An individual change to a file (or set of files).

•	**Fetch** - A primary command used to download contents from a remote repository.

•	**GIT** - A distributed version-control system for tracking changes in source code during software development.

•	**Github** - A web-based version-control and collaboration platform for software developers. Also, a hosted Git repository and social network for programmers.

•	**Merge** - A command that integrates the independent lines of development into a single branch.

•	**Merge Conflict** - A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits. When two branches are trying to merge, and both are edited at the same time and in the same file, Git won't be able to identify which version is to take for changes.

•	**Push** - A command that is used to upload local repository content to a remote repository.

•	**Pull** - A command that is actually a combination of two other commands, git fetch followed by git merge. First, it updates the current local working branch (currently checked out branch). Secondly, updates the remote tracking branches for all other branches.

•	**Remote** - A common repository that all team members use to exchange their changes.

•	**Repository** - A file location where you are storing all the files related to your project.
