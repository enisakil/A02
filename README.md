# A02

Enis Akil  
IS117  
Prof Chiusano  
February 13, 2024

## Git and Github Instructions

Git and Github are both extremely useful tools for developers in creating and making changes to projects, as well as collaborating with other developers. The first thing to understand is what Git and Github are. Git is an open source software that is used for tracking changes using a distrubited version control system, which means different versions of your projects and the changes you make are tracked while you're developing them. Github, as said in the name, acts as the hub for where these changes can be viewed and projects can be worked in tandem with other developers. Now that we know what Git and Github are, lets look at how to get started with each

### Git
In order to get started with git, you must first download it. Some versions of Mac and Linux might already come with git. In order to check if you have git installed on your machine, you would go to your computer's terminal and type the command "git version". If you see a version, then your computer already has git installed. If you don't see a version, then you must download git [here](https://git-scm.com/download). Once you've installed git you are now ready to make a github account and link the two.

### Github
Setting up an account with Github is a pretty straightforward process. It is essentially the same as making an account on any website. Go to the [Github website](https://github.com/) and follow the instructions to create an account.

### Linking the two
After you've installed Git and made an account with Github, the next step is to link the two. You do this in your computer's terminal. First you must set your git username with the command "git config --global user.name "*username*" ". To make sure this worked you can type "git config --global user.name" and the output should be what you entered in the quotes. The next thing is to set your email using "git config --global user.email "youremail@gmail.com"". Again, you can type "git config --global user.email" to confirm it's the right email. After doing this you should be prompted to authenticate your Github account, where you will then enter your email and password to confirm.

### You're in!
 
Your Git and Github are now setup. Congratulations! You can now edit code files locally on your IDE/code editor and push them to repositories on your Github. I won't touch too much on repositories and pushing changes aside from some basic definitions, but I will now talk about a potential code editor that you can use, Visual Studio Code.

### Visual Studio Code

Visual Studio Code, also known as VSCode for short, is a free code editor that allows you to begin coding quickly and easily. A code editor is where you will be doing most of your local code editing/changes, which you will then push to Github. In order to get started, you have to download VSCode, you can go to the site [here](https://code.visualstudio.com/download) and download the right version based on your operating system. Once you download it, you simply open up a folder and begin writing code. To use VSCode with git and Github, you can clone a repository on Github to your local machine, and then open it in VScode to edit the code. Once you are done editing you can commit and push the changes back to Github.

### IMPORTANT DEFINITIONS

- **Branch** - A section of a Github repository that one can use to test and develop new features to a project before adding them back to the main branch
- **Clone** - A command in git that allows you to make a copy of a repository to be put/opened in a new location
- **Commit** - A git command that captures the current changes made to a project, usually accompanied with a commit message to describe the changes.
- **Fetch** - A git command that downloads new data from a remote repository to your local machine/repo.
- **GIT** - An open source software for tracking changes in a distributed version control system.
- **Github** - A platform where Git users can collaborate on open source projects and share files.
- **Merge** - A git command that allows you to merge the code/commits from one branch into another.
- **Merge Conflict** - An issue that occurs when trying to merge two git branches together, typically due to multiple people adjusting the same lines in a file or deleting a file while someone else was modifying it.
- **Push** - A git command that moves the local repositiory content to a remote repository (typically used when moving local code changes to Github).
- **Pull** - A git command used to update the local version of a repository from a remote.
- **Remote** - A git repository that's hosted on the internet or other network (not on your local machine).
- **Repository** - The most basic element of git and Github. A storage or  collection of files for a project, including the many different versions, files, and branches made in the development of the project.

## Reference list:
[Most of setting up git and GitHub info](https://www.freecodecamp.org/news/introduction-to-git-and-github/)  

[Definition Resource #1](https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts)

[Definition Resource #2](https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull)

[Definition Resource #3](https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull)

[Git Documentation](https://git-scm.com/doc)
