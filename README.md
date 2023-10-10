# A02

## Part 1: Directions on Using Webstorm 

1. Download Webstorm: https://www.jetbrains.com/student/
2. Download **Git**: https://git-scm.com/downloads
3. Create a **Github** Account: https://github.com/join
4. Open Webstorm
5. Connect **Github**/**Git** with Webstorm
    * Press (CTRL+ALT+S) on your keyboard to active IDE settings and then select Version Control | Git   
    * Enter the path to the git.exe file on your computer
    * Click Ok
6. Add your **Github** Password to Webstorm 
   * In Webstorm, press (CTRL+ALT+S) to open System Preferences 
   * Select Appearance and Behavior | System Settings | Passwords 
   * In KeePass, type the location where your password file is located 
   * Click Ok
7. In **Github**, Create a **Repository**
   * Press the + at the top of the page 
   * Create a New **Repository** by clicking New Repository
   * Your first **Repository** is set up.
   * Make the **Repository** public, add the ReadMe file, and click Create.
8. Create a **Repository** from Webstorm
   * Select VCS and Import into Version Control
   * Create a **git** repository
   * Name the **Repository**
   * Click Ok
9. Import a **Repository** from Github
    * From the Main Page, Select Checkout from Version ControL
    * Select **Git** OR
    * From Within Webstorm Select VCS
    * Select Checkout from Version Control
    * Select **Git**
    * Enter the **Github Repository** Name
    * Enter the local path name
    * Click **Clone**
10. Create a Webstorm File
    * Choose File
    * Click on HTML
    * Click HTML 5 (This will create your HTML File)
    * Or Click on File
    * And then Click on Stylesheet (This will create your CSS File)
11. Add Files to Git
    * The Add to **Git** Dialog will open after the previous step is completed
    * Click Add to add the files to **Git**
12. Commit Your Changes
    * Make any changes to the index.html file you just added to **Git**
    * Add a **Commit** Message
    * Click on **Commit**
13. Push Change to **Remote Repository** 
    * Click (CTRL+SHIFT+K)
    * Or Click VCS | Git | **Push**
14. Your file will now be on Github
15. Set up Github Pages
    * Click Settings
    * Check the **Repository** name
16. Choose Github Pages Location
    * Select "Main **branch**"
17. Check your Github Pages
    * Copy the Github.io URL into a browser
18. How to Pull a Request from Github
    * On Github, navigate to the **Repository**
    * Click on the Branch Menu, and choose the one that contains your **commits**
    * Above the list of files, click Compare and **pull** request to create a **pull** request for the branch
    * Use the branch dropdown menu to select the **branch** you would like to work with and **merge** changes
    * Click on the compare **branch** drop-down menu to choose the topic **branch** that you made your changes in
    * Type in the title and description of the **pull** request
    * Finally, click Create **Pull** Request to create the **Pull** request
19. How to Fetch Changes on Github
    * Use *git fetch* to receive the work done by other people on Github.
    * Enter *git fetch REMOTE-NAME* into the terminal.
20. How to Resolve Merge Conflicts
    * Under the **Repository** name, click on **Pull** Requests
    * In the **Pull** Requests List, click on the **pull request** with the merge conflict you would like to resolve
    * Click on Resolve conflicts



## Part 2: Glossary 
**Branch**: A repository contains branches, and can be helpful when trying to make changes without disrupting the main or primary branch. Changes made in the branch can later be merged back with the main or primary branch. 
</br>
**Clone**: It is a local copy of a repository. Files can be edited on another editor and be uploaded to Git without being online. The repository that has been cloned is connected to the remote version online, so whenever you are online, you are able to push the local changes you have made to the remote version online.
</br>
**Commit**: To make changes to a file or a set of files. When a commit is made, your work is saved, and Github will generate a unique ID (aka the "SHA" or the hash) to keep a record of the saved changes. It will also keep a record of who made those changes and when they made those changes. Commits have a brief description that displays what changes were made. 
</br>
**Fetch**: When changes are being added from the remote repository to a local copy without committing those changes. 
</br>
**GIT**: It is an open source program that tracks changes made in text files. It was written by the author of the Linix operating system, and serves as the foundation of Github.
</br>
**Github**: It is an open source version control system that allows collaborator(s) to track their changes by uploading their source code here. They can also collaborate with other people and revert to a previous version if bugs are introduced. 
</br>
**Merge**: It takes the changes from one branch and applies it to another branch. A merge can be done via a "pull request" or via the command line.
</br>
**Merge Conflict**: When branches are merged, conflicts may happen. For instance, if people are making changes to the same line, or if one person tries to edit the file while another person deletes the file.
</br>
**Push**: To update the remote repository with committed changes you have made locally. You can "push" these changes onto the remote repository after changing them locally, and that will allow others to access it. 
</br>
**Pull**: The ability to fetch changes and merge them. For example, you can "pull" in the changes made to the remote repository, and update your local copy with them.
</br>
**Remote**: The version of a repository or branch that is hosted on another server, such as on Github.com. As changes are made, the repository/branch on Github is updated to display the changes. 
</br>
**Repository**: It is considered to be the most basic element of Github. It can be thought of as a project's folder, and includes all of the project's files. It also includes each file's revision history. Repositories can be public or private and can include one or more collaborators. 
</br>

### Sources Used
Set up a Git repository | WebStorm. (n.d.). WebStorm Help. https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html

‌Creating a pull request. (n.d.). GitHub Docs. Retrieved October 10, 2023, from https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request

‌Getting changes from a remote repository. (n.d.). GitHub Docs. https://docs.github.com/en/get-started/using-git/getting-changes-from-a-remote-repository

‌Resolving a merge conflict on GitHub. (n.d.). GitHub Docs. https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github

‌

