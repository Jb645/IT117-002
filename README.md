# IT117-002
## **Terms**
- ***Branch***: A "branch" is a line of development. The most recent commit on a branch is referred to as the tip of that branch. The tip of the branch is referenced by a branch head, which moves forward as additional development is done on the branch. A single Git repository can track an arbitrary number of branches, but your working tree is associated with just one of them (the "current" or "checked out" branch), and HEAD points to that branch.
- ***Clone***: Clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository (visible using git branch --remotes), and creates and checks out an initial branch that is forked from the cloned repository’s currently active branch. After the clone, a plain git fetch without arguments will update all the remote-tracking branches, and a git pull without arguments will in addition merge the remote master branch into the current master branch, if any 
- ***Commit***:  Record changes to the repository. By using git-add to incrementally "add" changes to the index before using the commit command. By using git-rm to remove files from the working tree and the index, again before using the commit command.
- ***Fetch***: Download objects and refs from another repository. git fetch can fetch from either a single named repository or URL, or from several repositories at once if <group> is given and there is a remotes.<group> entry in the configuration file. Otherwise no remote turns by default to using origin.
- ***GIT***: is a software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).
- ***Github***: is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management (SCM) functionality of Git, plus its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project.
- ***Merge***: Join two or more development histories together. ncorporates changes from the named commits (since the time their histories diverged from the current branch) into the current branch. This command is used by git pull to incorporate changes from another repository and can be used by hand to merge changes from one branch into another.
- ***Merge Conflict***: is an event that occurs when Git is unable to automatically resolve differences in code between two commits.
- ***Push***: Update remote refs along with associated objects. The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo.
- ***Pull***: Fetch from and integrate with another repository or a local branch. The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
- ***Remote***: A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server.
- ***Repository***: A Git repository is the .git/ folder inside a project. This repository tracks all changes made to files in your project, building a history over time. Meaning, if you delete the .git/ folder, then you delete your project’s history.


## **Tutorial Git/Webstorm/Github**
#### Sign Up for Jetbrains/download Webstorm
1. go to www.jetbrains.com/student/
2. click on apply now under "Who can free Individual licenses for education"
3. fill in the information depending on your status (remember that the email adress most be from your university) and after that click on "I have read and I accept the JetBrains Account Agreement"
4. Verify your email
5. click on the person icon in the between the magnifing glass and shopping cart.
6. sign in with existing account with your email and password your submitted on step 3
7. In the License tab click on the link by the name of "webstorm" under following products included
8. click on the blue button by the name download
9. click on the download button under your operating system of choise **(Windows/ Mac/ Linux)**
10. click on run and save the file.
11. find the file and click to set up webstorm (have everything recomended) (more instructions later)

#### Download GIT (for Windows)
1. Go to https://git-scm.com/downloads
2. Click on Windows and save the file for the set up
3. Find the file and double click it
4. Choose the place where you want to install git and its utilities (make sure git bash and GUI is checked)
5. You can leave vim as the default editior or choose your own(must know what you are doing)
6. Choose the recomended options and just keep clicking next untill starts installing
7. After installing just launch it
8. After launching it you canchange your global user name and email for your GitHub Account to make it easier when getting your repository (commands: git config --global user.name "Username" , git config --global user.email johndoe@example.com)

#### Setup GITHUB
1. Go to https://github.com
2. Click on sign Up on the top right
3. Fill your username, email and password.
4. Verify your account, and create account.
5. Select plan (free)
6. Fill why you are using GitHub(you can skip the this part if you want) and complete the set up
7. Verify email
8. Create a new repository by filling out the name(this is IT117-002) and then just click create repository

#### Setup WebStorm
1. In the Webstorm App leave click on "New project" button inthe projects tab
2. In "Empty Project" choose the location for your webstorm project and click create
3. On the top click on VCS > Enable Version Control Integration
4. Choose GIt and click on OK
5. Ctrl+Alt+S for system preferences of Webstorm
6. click on version Control tab and on Git and click on the "test" button on "Path to Git executable"
7. Now you can test it by right clickin on the folder right under project on the left side
8. choose New > HTML file.
9. You can change the title if you want but rember to add a <p>Hello World</p> in between the 2 body tags
10. Clik on "Git" on the top between "Tools" and "Window"
11. Click Connect
12. Choose files to commit (just the HTML file)
13. make a commit Message and click the commit Button
14. Fill your GitHub Information the name and Email
15. To add to online Git Repository click Git > GitHub> Share Project on GitHUb
16. Fill in the info from the GitHub (repository Name, share by > add Account)
17. Authorize in Github on jetBrains pop up and sign in with github account
18. Click on share back on Webstorm
19. Go to GitHub.com and go to your repository, then to settings (settings might be on "..." if browser is not fullscreen)
20. change source to None and save
21. Scrolls down to "source" right above the danger Zone if background not blue change none back to master
22. wait or keep reloading the page until it says your site is published above source
23. click on the link provided by the published, you should see a hello world text on your screen
24. Congratulations you are done, now any commits on the future should be published here
25. You can Also click on the browser in the html file right side to see your changes (these are not the github ones, remember to commit if you want to see it on gitHUB)
