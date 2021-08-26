# Quick Intro to _Git_ / _GitHub_ 


## 🤓 Course Overview & Learning Outcomes

> The goal of this short intro is to briefly introduce you to both _Git_ & _GitHub_, highlighting how they can be used in _Science_. 🔬 🧪 🚀


## _Git_ & _GitHub_ | The Basics:

- _Git_ is a **distributed Version Control System (VCS)**, which means it is a useful tool for easily tracking changes to your code, collaborating, and sharing. With _Git_ you can easily track the changes you make to your files so you always have a record of what you have worked on and can always revert back to an older version if needed. It also makes working with others easier—groups of people can work together on the same project and merge their changes into one **final source**!

- _GitHub_ is a way to use the same power of _Git_ with an user-friendly interface. It is used across the _Science_ world and beyond to collaborate and maintain the history of projects.


## Getting Started | Instalations:

1. If you do not have one already, please create a [GitHub Account](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
2. Please download & install [_Visual Studio Code_](https://code.visualstudio.com/) on your machine.
3. Please download & install [_Git_](https://git-scm.com/downloads) on your machine.  
4. Please download & install [_GitHub Desktop_](https://desktop.github.com/) on your machine. (**Optional**)

NOTES:

- Do take sometime to mull over the GitHub user name you will choose. This is important because you want people to be able to find your GitHub Account with ease, and 
- Make sure to download the specific versions for your operating system.    
- Do not be shy and just say **Next**, **Next** (...) **Next** (when needed).
- You may want to reboot your system after these installations are completed.
- Instead of _VSC_ you could use [_Atom_](https://atom.io/), but I would largely favour _VSC_ over it.
***

## 💻 GitHub Jargon To Know

### Repositories

A repository is where your project work happens -- think of it as your project folder (I myself like to have one for each individual study/article I work on). A _repository_ contains all of your project’s files and revision history. You can work within a repository alone or **invite others to collaborate with you on those files**. You can find an example of a repository [here](https://github.com/g-pacheco/FeralPigeonGenomics). Take some time to navigate through and get yourself familiaried. 

### Cloning 

When a _repository_ is created with _GitHub_, it is stored remotely in Narnia (aka The ☁️). You can clone a _repository_ to create a local copy on your computer (your Precious!) and then use _Git_ to sync the two. This makes it easier to fix issues add/or remove files as well as add larger commits (your comments on specific changes your have made). You can also use the editing tool of your choice (like _VSC_) as opposed to the _GitHub User Interface_ (this page you are looking at right now). Cloning a repository also pulls down all the repository data that _GitHub_ has at that point in time, including all versions of every file and folder for the project! This can be helpful if you experiment with your project **and then realize you liked a previous version more**. To learn more about cloning, read ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Committing & Pushing

**Committing** & **Pushing** are how you can add the changes you made on your local machine to the remote repository in _GitHub_. That way your peer scientists can see your latest work when you are ready to share it. You can make a commit when you have made changes to your project that you want to _checkpoint_. You can also add a helpful _commit message_ to remind yourself or your teammates what work you did (e.g. “I changed the colour of the samples' names.”).

Once you have a commit or multiple commits that you are ready to add to your repository, you can use the push command to add those changes to your remote repository. Committing and pushing may feel odd at first, but I promise you will get used to it 🙂
***

## 💻 GitHub Jargon To Know 

### Repositories
 
We mentioned repositories already, they are where your project work happens, but let us talk a bit more about the details of them! As you work more on GitHub you will have many repositories which may feel confusing at first. Fortunately, your ["GitHub dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) helps to easily navigate to your repositories and see useful information about them. Make sure you are logged in to see it!

Repositories also contain **README**s. You can add a README file to your repository to tell other people why your project is useful, what they can do with your project, and how they can use it. We are using this README to communicate how to learn Git and GitHub with you. 😄 
To learn more about repositories read ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) and ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branches
You can use branches on GitHub to isolate work that you do not want merged into your final project just yet. Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. Typically, you might create a new branch from the default branch of your repository—main. This makes a new working copy of your repository for you to experiment with. Once your new changes have been reviewed by a teammate, or you are satisfied with them, you can merge your changes into the default branch of your repository.
To learn more about branching, read ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
A fork is another way to copy a repository, but is usually used when you want to contribute to someone else’s project. Forking a repository allows you to freely experiment with changes without affecting the original project and is very popular when contributing to open source software projects!
To learn more about forking, read ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Pull requests
When working with branches, you can use a pull request to tell others about the changes you want to make and ask for their feedback. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add more changes if need be. You can add specific people as reviewers of your pull request which shows you want their feedback on your changes! Once a pull request is ready-to-go, it can be merged into your main branch.
To learn more about pull requests, read ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues
Issues are a way to track enhancements, tasks, or bugs for your work on GitHub. Issues are a great way to keep track of all the tasks you want to work on for your project and let others know what you plan to work on. You can also use issues to tell a favorite open source project about a bug you found or a feature you think would be great to add!

For larger projects, you can keep track of many issues on a project board. GitHub Projects help you organize and prioritize your work and you can read more about them [in this "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). You likely won’t need a project board for your assignments, but once you move on to even bigger projects, they are a great way to organize your team’s work!
You can also link together pull requests and issues to show that a fix is in progress and to automatically close the issue when someone merges the pull request.
To learn more about issues and linking them to your pull requests, read ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### Your user profile

Your profile page tells people the story of your work through the repositories you are interested in, the contributions you have made, and the conversations you have had. You can also give the world a unique view into who you are with your profile README. You can use your profile to let other researchers know all about you! 
To learn more about your user profile and adding and updating your profile README, read ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Using markdown on GitHub 

You might have noticed already, but you can add some fun styling to your issues, pull requests, and files. ["Markdown"](https://guides.github.com/features/mastering-markdown/) is an easy way to style your issues, pull requests, and files with some simple syntax. This can be helpful to organize your information and make it easier for others to read. You can also drop in gifs and images to help convey your point!
To learn more about using GitHub’s flavor of markdown, read ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Engaging with the GitHub community

The GitHub community is vast. There are many types of people who use GitHub in their day to day—students like you, professional developers, hobbyists working on open source projects, and explorers who are just jumping into the world of software development on their own. There are many ways you can interact with the larger GitHub community, but here are three places where you can start. 

#### Starring repositories 

If you find a repository interesting or you want to keep track of it, star it! When you star a repository it’s also used as a signal to surface better recommendations on github.com/explore. If you’d like to get back to your starred repositories you can do so via your user profile. 
To learn  more about starring repositories, read ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Following users 

You can follow people on GitHub to receive notifications about their activity and discover projects in their communities. When you follow a user, their public GitHub activity will show up on your dashboard so you can see all the cool things they are working on. 
To learn more about following users, read ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Browsing GitHub Explore 

GitHub Explore is a great place to do just that … explore :smile: You can find new projects, events, and developers to interact with.

You can check out the GitHub Explore website [at github.com/explore](https://github.com/explore). The more you intereact with GitHub the more tailored your Explore view will be.


## 📚  Additional Resources
 
* [A Short Video Explaining What GitHub Is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git & GitHub Learning Resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
* [How to Use GitHub Branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git Training Materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education Community Forum](https://education.github.community/)
* [GitHub Community Forum](https://github.community/)
***
