# 02. Getting Started With Git :

## 2.1 : What Is Git ?

Git is a distributed version control system that is used for tracking changes in source code during software development. It was created by Linus Torvalds in 2005 and is now maintained by the Linux Foundation.

Git is designed to handle large projects efficiently and is widely used in the software development industry.

## 2.1 : Why Use Git ?

Git is a powerful tool that helps developers manage their codebase efficiently. It allows developers to track changes, collaborate with others, and manage large projects. Git is also used for version control, which means that developers can revert to previous versions of their code if needed.

Git is a distributed version control system, which means that each developer has a copy of the entire codebase. This allows developers to work on the same codebase without having to worry about conflicts.

Git is also a distributed version control system, which means that each developer has a copy of the entire codebase. This allows developers to work on the same codebase without having to worry about conflicts.

## 2.2 / 2.3 : How Git Works

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/7a7ee0a1-33b1-47dd-aacd-a67cc9ec4092" />

## 2.4 : Git Alternatives

Here are some popular alternatives to Git:

1. **Mercurial** (https://www.mercurial-scm.org/) - A distributed version control system that is easy to use and fast.
2. **Subversion** (https://subversion.apache.org/) - A centralized version control system that is widely used in enterprise environments.
3. **Perforce** (https://www.perforce.com/) - A version control system that is known for handling large codebases and binary files.
4. **Bazaar** (https://bazaar.canonical.com/) - A distributed version control system that is user-friendly and flexible.
5. **CVS** (https://www.nongnu.org/cvs/) - An older version control system that is still used in some legacy projects.

# 03. Git Installation :

## 3.1 : Mac Os Installation

To install Git on Mac OS, you can use the following steps:

1. Open the Terminal application.
2. Run the following command to install Homebrew: <br> **/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"**
3. Run the following command to install Git: <br> **brew install git**

## 3.2 : Windows Installation

To install Git on Windows, you can use the following steps:

1. Download the Git installer from the Git website (https://git-scm.com/downloads/win).
2. Run the installer and follow the instructions to complete the installation.
3. Open the Git Bash application to start using Git.

## 3.3 : Linux Installation

To install Git on Linux, you can use the following steps:

1. Open the Terminal application.
2. Run the following command to install Git: <br>
**sudo apt-get update** <br>
**sudo apt-add-repository ppa:git-core/ppa** <br>
**sudo apt-get update** <br>
**sudo apt-get install git**

# 04. Git Commands :

## 4.1 : List of Git Commands

1. **git init :** Initialize a new Git repository <br>
2. **git clone :** Clone an existing repository <br>
3. **git status :** Show the working tree status <br>
4. **git add :** Add file contents to the index <br>
5. **git commit :** Record changes to the repository <br>
6. **git push :** Update remote refs along with associated objects <br>
7. **git pull :** Fetch from and integrate with another repository or a local branch <br>
8. **git branch :** List, create, or delete branches <br>
9. **git checkout :** Switch branches or restore working tree files <br>
10. **git merge :**	Join two or more development histories together <br>
11. **git log :** Show commit logs <br>
12. **git diff :** Show changes between commits, commit and working tree, etc <br>
13. **git reset :**	Reset current HEAD to the specified state <br>
14. **git rm :** Remove files from the working tree and from the index <br>
15. **git stash :**	Stash the changes in a dirty working directory away <br>
16. **git tag :** Create, list, delete or verify a tag object signed with GPG <br>
17. **git fetch :** Download objects and refs from another repository <br>
18. **git remote :** Manage set of tracked repositories <br>
19. **git rebase :** Reapply commits on top of another base tip <br>
20. **git bisect :** Use binary search to find the commit that introduced a bug <br>
21. **git grep :** Print lines matching a pattern <br>
22. **git show :** Show various types of objects <br>
23. **git archive :** Create an archive of files from a named tree <br>
24. **git cherry-pick :** Apply the changes introduced by some existing commits <br>
25. **git blame :** Show what revision and author last modified each line of a file <br>
26. **git clean :** Remove untracked files from the working tree <br>

## 4.2 : Git Help

1. **git help**

## 4.3 : Adding Configuration (Git Config)

git config --global user.name "John Doe" <br>
git config --global user.email "john.doe@example.com"

### More Git Config Commands

1. **git config --global user.name "John Doe" :** Set the name for all repositories on your system <br>
2. **git config --global user.email "john.doe@example.com" :** Set the email for all repositories on your system <br>
3. **git config --global core.editor "code --wait" :** Set the default text editor for Git to Visual Studio Code <br>
4. **git config --global merge.tool "meld" :** Set the default merge tool to Meld <br>
5. **git config --global diff.tool "meld" :** Set the default diff tool to Meld <br>
6. **git config --global alias.st status :** Create a shortcut alias for the **git status** command <br>
7. **git config --global alias.co checkout :** Create a shortcut alias for the **git checkout** command <br>
8. **git config --global alias.ci commit :** Create a shortcut alias for the **git commit** command <br>
9. **git config --global alias.br branch :** Create a shortcut alias for the **git branch** command <br>
10. **git config --global color.ui auto	:** Enable automatic coloring of Git command output <br>
11. **git config --global core.autocrlf true :** Set automatic conversion of line endings (useful for Windows users) <br>
12. **git config --global core.safecrlf warn :** Warn if a file has mixed line endings <br>
13. **git config --global push.default simple :** Set the default behavior for **git push** to **simple** <br>

# 05. Your First Git Repository :

## 5.1 : What Is A Git Repository

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/8a4bb8f0-f962-4c01-be35-0fe462f0ed5e" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/842e9577-383c-45be-b608-61319db2b092" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/1062f7a2-f86e-4181-9352-0a96d3dc8c24" />

## 5.2 : Working Directory And Git Init

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/0142c592-b13f-45fa-9fcd-c4855f8d3ffa" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/896c49ce-d0c5-464a-a645-5d0da2506d21" />

## 5.3 : Create Working Directory With Git

## 5.4 : Initialize Git Repository (Git Init)

## 5.5 : Working With Global And Local Configuration

## 5.6 : Hidden .Git Folder

# 06. Tracking Changes :

## 6.1 : Intro

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/0434e2b3-e743-4968-ba4b-fbd2c7d33f0c" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/e9145e6a-41be-4970-9e19-8783331e9843" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/b88b6196-da3d-4100-b5b6-51a2d406776d" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/403da006-513a-4089-b5bf-4b4a4a27c909" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/e5a84621-a8a8-47d9-995a-764d4a6be6c8" />

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/5795e411-7980-42d2-a94f-a6167a9af73c" />

# 09. Outro :

## 9.2 : 12 Most Common Git Commands

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/81acc292-a1b3-4898-a3a8-30d5843c0c9c" />

## 9.3 : 10 Most Common Git Commands

<img width="925" alt="Image" src="https://github.com/user-attachments/assets/29d22cd1-09ee-4fdb-a3fd-78dcf573613f" />

## Additional Info :

### Adding a new SSH key to your GitHub account :
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=mac

### Git Guide :
https://github.com/git-guides

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
