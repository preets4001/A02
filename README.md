Glossary
Branch – A separate line of development in a GIT repository, allowing multiple versions of a project to exist simultaneously.
Clone – A copy of a remote repository that is downloaded to a local machine for development.
Commit – A saved change in GIT, capturing a snapshot of the current state of the project.
Fetch – A command that retrieves the latest changes from a remote repository without merging them.
GIT – A version control system that tracks changes in source code during software development.
GitHub – A web-based platform for hosting and managing GIT repositories, facilitating collaboration.
Merge – The process of integrating changes from one branch into another.
Merge Conflict – An issue that arises when GIT cannot automatically reconcile differences between two merged branches.
Push – A command that uploads local commits to a remote repository.
Pull – A command that fetches and integrates changes from a remote repository into a local branch.
Remote – A version of a repository stored on a server, allowing for collaboration.
Repository – A storage location for a project's files, history, and GIT version tracking.


Git, WebStorm, and GitHub Tutorial

## Introduction  
This tutorial provides a step-by-step guide on how to use **Git** with **WebStorm** and **GitHub** for version control and collaboration. By following this guide, you will learn how to:  
- Set up Git and connect it with WebStorm  
- Clone a repository from GitHub  
- Make changes and commit them  
- Push and pull changes  
- Work with branches and resolve merge conflicts  

---


## Step 1: Configure Git in WebStorm  
1. Open **WebStorm**.  
2. Go to **File > Settings > Version Control > Git** (Windows/Linux) or **WebStorm > Preferences > Version Control > Git** (Mac).  
3. Ensure that WebStorm detects Git automatically. If not, manually set the path to Git:  
   - Windows: `C:\Program Files\Git\bin\git.exe`  
   - Mac/Linux: `/usr/bin/git`  
4. Click **Test** to verify the configuration.  
5. Click **Apply** and **OK**.  

---

## Step 2: Clone a Repository from GitHub  
1. Open WebStorm.  
2. Go to **File > New > Project from Version Control > Git**.  
3. Enter the **GitHub repository URL**.  
4. Choose a local directory where you want to save the project.  
5. Click **Clone**.  

---

## Step 3: Make Changes and Commit  
1. Open any file in the project.  
2. Make your desired changes.  
3. Go to **VCS > Git > Commit** or press `Ctrl + K` (Windows/Linux) or `Cmd + K` (Mac).  
4. Write a meaningful commit message.  
5. Click **Commit** (or **Commit and Push** to send changes immediately).  

---

## Step 4: Push Changes to GitHub  
1. After committing, go to **VCS > Git > Push** or press `Ctrl + Shift + K` (Windows/Linux) or `Cmd + Shift + K` (Mac).  
2. Select the remote repository and click **Push**.  

---

## Step 5: Pull Changes from GitHub  
1. Go to **VCS > Git > Pull**.  
2. Choose the remote repository and branch.  
3. Click **Pull** to update your local project with remote changes.  

---

## Step 6: Work with Branches  
### Create a New Branch  
1. Go to **VCS > Git > Branches**.  
2. Click **New Branch** and enter a branch name.  
3. Click **Checkout** to switch to the new branch.  

### Merge Branches  
1. Switch to the branch you want to merge **into** (e.g., `main`).  
2. Go to **VCS > Git > Merge Changes**.  
3. Select the branch you want to merge and click **Merge**.  

### Resolve Merge Conflicts  
1. If a **Merge Conflict** occurs, WebStorm will highlight conflicting files.  
2. Open the conflicting file and manually resolve differences.  
3. After resolving, commit the changes.  

---


