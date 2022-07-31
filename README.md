# 0x01. Git :file_folder:
## Resources:open_book:
- [*Resources to learn Git*](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [*About READMEs*](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
- [*How to write a Git commit message*](https://cbea.ms/git-commit)

**Resources for advanced tasks**(Read only after finishing the mandatory tasks):

- [*Learning branching*](https://learngitbranching.js.org)
- [*Effective pull requests and other good practices for teams using GitHub*](https://codeinthehole.com/tips/pull-requests-and-other-good-practices-for-teams-using-github/)

# Learning Objectives:page_with_curl:
At the end of this project, you are expected to be able to [*explain to anyone*](https://fs.blog/feynman-technique/),**without the help of Google:**

- What is source code management
- What is Git
- What is GitHub
- What is the difference between Git and GitHub
- How to create a repository
- What is a README
- How to write good READMEs
- How to commit
- How to write helpful commit messages
- How to push code
- How to pull updates
- How to create a branch
- How to merge branches
- How to work as collaborators on a project
- Which files should and which files should not appear in your repo

## Requirements:bookmark:
- A `README.md`file at the root of the `alx-pre_course repo`, containing a description of the repository
- A `README.md`file, at the root of the folder of this project (i.e. `0x01-git`), describing what this project is about
- **Do not use GitHub’s web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
- Your answer files should only contain the command, and nothing else

# More Info
## Basic usage
At the end of this project you should be able to reproduce and understand these command lines:
~~~~
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
~~~~
## Tasks:scroll:
## 0. Create and setup your Git and GitHub account
#### Step 0 - Create an account on GitHub [if you do not have one already]
You will need a GitHub account for all your projects at ALX. If you do not already have a github.com account, you can create an account for free [here](https://github.com/login)

#### Step 1 - Create a Personal Access Token on Github
To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow [this tutorial](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) to create a token.

#### Step 2 - Update your profile on the Intranet
Update your Intranet profile by adding your Github username

#### Step 3 - Create your first repository
Using the graphic interface on the [github website](https://github.com/login), create your first repository.

- Name: `alx-pre_course`
- Description:`I'm now a ALX Student,this is my first repository as a full-stack engineer`
- Public repo
- No `README`, `.gitignore`, or license

####Step 4 - Open the sandbox
- On the intranet, just under the task, click on the button `>_Get a sandbox` and `run` to start the machine.

- Once the container is started, click on `>_Webterm` to open a shell where you can start work from.

#### Step 5 - Clone your repository
On the webterm of the sandbox, do the following:

- Clone your repository
~~~~
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git                  
Cloning into 'alx-pre_course'...
warning: You appear to have cloned an empty repository.
~~~~
**Replace {YOUR_PERSONAL_TOKEN} with your token from step 1**

**Replace {YOUR_USERNAME} with your username from step 0 and 1**

#### Step 6 - Create the README.md and push the modifications       
