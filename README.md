
# GitHub Commands

This cheat sheet provides a list of commonly used Git commands to help you manage your version control and collaborate on  projects.

## Table of Contents

- [Getting Started](#getting-started)
- [Creating a Repository](#creating-a-repository)
- [Cloning a Repository](#cloning-a-repository)
- [Working with Branches](#working-with-branches)
- [Committing Changes](#committing-changes)
- [Pull Requests](#pull-requests)
- [Working with Remotes](#working-with-remotes)
- [Git Tags](#git-tags)
- [Useful Tips](#useful-tips)
- [Contributing](#contributing)

## Getting Started

Make sure you have Git installed on your local machine. You can download it from [here](https://git-scm.com/).



## Getting Started

Make sure you have Git installed on your local machine. You can download it from [here](https://git-scm.com/).

## Creating a Repository

1. **Initialize a New Repository:**

   **git init**

Create a Repository on GitHub:
Visit GitHub, log in, and click on the "New" button to create a new repository.

2. **Add a Remote Repository:**

**git remote add origin <repository-url>**

### Cloning a Repository
**git clone <repository-url>**

### Working with Branches
1.**Create a New Branch:**
**git checkout -b <branch-name>**

2.**Switch to an Existing Branch:**
**git checkout <branch-name>**

3.**List Branches:**
**git branch**

4.**Delete a Branch:**
**git branch -d <branch-name>**

### Committing Changes
**1.Stage Changes:**
**git add .**

**2.Commit Changes:**
**git commit -m "Your commit message here"**

**3.Push Changes to Remote:**
**git push origin <branch-name>**

### Pull Requests
**Create a Pull Request:**
Visit your repository on GitHub and click on "New Pull Request" to start a pull request.

**Merge a Pull Request:**
After review, merge the pull request on GitHub.

### Working with Remotes

**1.List Remote Repositories:**
**git remote -v**

**2.Fetch Changes from Remote:**
**git fetch**

**3.Pull Changes from Remote:**
**git pull**

### Git Tags
**1.Create a Tag:**
**git tag -a <tag-name> -m "Tag description"**

**2.Push Tags to Remote:**
**git push origin --tags**

### Useful Tips
**Always make meaningful commit messages.**

**Keep your local repository up to date with git pull before making changes.**

**Document your project's README.md to help others understand your repository.**

### Contributing
*Feel free to contribute to this cheat sheet by creating a pull request. Add more GitHub commands or improve existing ones to make it even more helpful.*

***Happy coding! 🚀***
