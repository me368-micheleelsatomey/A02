# A02 IS 117001
Create a Github Account with Git/Webstorm/Github/Tutorial. Define Terms

This tutorial provides the step-by-step instructions for setting up and using Git, WebStorm, and GitHub.

Step-by-Step Tutorial on Setting Up Git, WebStorm, and GitHub:

Step 1: Install Git

  a) Get Git by visiting Git Downloads, the official website. URL: https://git-scm.com/downloads
  b) Comply with the Windows, macOS, or Linux installation guidelines.
  c) Type git --version into your terminal (or Windows command prompt) to see whether Git was installed successfully.
  This ought to provide the Git version number.
  
Step 2: Install WebStorm

  a) Go to JetBrains and download WebStorm: WebStorm Download. URL: https://www.jetbrains.com/webstorm/download/#section=windows
  b) Install it by following your operating system's instructions.
  c) Use your GitHub account to set up WebStorm:
        1) Launch Webstorm.
        2) Choose File > Settings > Git Version Control.
        3) Verify that WebStorm accurately recognizes Git.
        4) Click Settings > Version Control > GitHub, add your GitHub account, and then log in.
        
Step 3: Use Webstorm to Create a Local Git Repository

  a) Start a new project in WebStorm.
  b) Right-click your project folder and choose Git > Initialize Git Repository to set up Git in your project.
  b) To tell Git which files (like node_modules/) to ignore, create a.gitignore file.
  d) Make a new file (for example, index.html), then choose VCS > Commit to commit the file.
  f) Commit a message, such as "Initial commit."
  
Step 4: Push to GitHub

  a) Connect GitHub to your local repository:
      1) Select Push under VCS > Git.
      2) If you haven't previously connected your GitHub account, WebStorm will prompt you to do so.
      3) Choose the A02 repository that you established.
  b)  Push your changes:
       git push origin main

Step 5: Pulling from GitHub

  a) If you want to fetch the latest changes from the remote repository:
        git pull origin main



GLOSSARY:

1) Branch: A branch is an independent line of development within a Git repository. The default branch is called main or master.

2) Clone: Cloning a repository means making a local copy of a remote Git repository. You can clone with the following command:
git clone <repository-url>

3) **Commit**: A commit represents a saved snapshot of changes in a Git repository. You create a commit with:
git commit -m "Commit message"

4)**Fetch**: Fetching gets the latest changes from the remote repository but doesn’t merge them into your working directory.
git fetch

5) **Git**: Git is a distributed version control system that tracks changes in source code during software development.

6) **GitHub**: GitHub is a platform built around Git that allows for remote repository hosting and collaboration on code.

7) Merge: Merging integrates changes from one branch into another, usually from a feature branch into main.

8) Merge Conflict: A merge conflict occurs when two branches modify the same part of a file differently, and Git cannot merge them automatically.

9) **Push**: Pushing sends your committed changes to a remote repository, such as GitHub.
git push origin main

10) **Pull**: Pulling updates your local repository with changes from a remote repository. It is essentially a fetch followed by a merge.
git pull origin main

11) **Remote**: A remote repository is a version of your project hosted on the internet or network. GitHub repositories are an example of remotes.

12) **Repository**: A repository is a storage space where your project's code and history are stored. It can be either local (on your machine) or remote (on GitHub).


REFERENCES:

1) https://docs.github.com/en/get-started/start-your-journey/hello-world
2) https://phoenixnap.com/kb/how-to-use-git
3) https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html
4) https://www.w3schools.com/git/
