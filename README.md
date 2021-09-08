# Quick Intro to _Git_ / _GitHub_ 


## 🤓 Overview & Learning Outcomes

> The goal of this short intro is to briefly introduce you to both _Git_ & _GitHub_, highlighting how they can be used in _Science_. 🔬 🧪 🚀


## _Git_ & _GitHub_ | The Basics:

- _Git_ is a **distributed Version Control System (VCS)**, which means it is a useful tool for easily tracking changes to your code, collaborating, and sharing. With _Git_ you can easily track the changes you make to your files so you always have a record of what you have worked on and can always revert back to an older version if needed (if you have coded a tiny bit you know that this WILL be needed 🤭). It also makes working with others easier — groups of people can work together on the same project and merge their changes into one **final source**!

- _GitHub_ is a way to use the same power of _Git_ with an user-friendly interface. It is used across the _Science_ world and beyond to collaborate and maintain the history of projects.


## Getting Started | Instalations:

1. If you do not have one already, please create a [GitHub Account](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)  

¡CAUTION! ✋  

Two things here. Frist, take a while to mull over your _GitHub User Name_ due to a few factors:  

* You want to have something that others can remember (and associte to your name) easily. Besides, it is possible to host a webpage on GitHub for free (usually, this is a paid service). However, the domain of this page needs to be YOUR-USER-NAME.github.io. Thus, it advisable that you choose a user name with that possibility in mind. [Here](https://g-pacheco.github.io/) is my personal webpage I host on _GitHub_, and [here](https://mcruf.github.io/) and [here](https://jcerca.github.io/) are extra examples.  
* If you are are PhD student, I would really encorage you to apply for a GitHub Student account though this [link](https://education.github.com/pack). It is totally free, and it will give you some extra powers (usually given to paid account). So, I really recommend that you use your student status while you still can 😗 

2. Please download & install [_Visual Studio Code_](https://code.visualstudio.com/) on your machine.
3. Please download & install [_Git_](https://git-scm.com/downloads) on your machine.  
4. Please download & install [_GitHub Desktop_](https://desktop.github.com/) on your machine. (**Optional**)

NOTES:
  
- Do not be shy and just say **Next**, **Next** (...) **Next** (when needed).
- You may want to reboot your system after these installations are completed.
- Instead of _VSC_ you could use [_Atom_](https://atom.io/), but I would largely favour _VSC_ over it.
***

## 💻 _GitHub_ Jargon To Know

### Repositories

A repository is where your project work happens -- think of it as your project folder (I myself like to have one for each individual study/article I work on). A _repository_ contains all of your project’s files and revision history. You can work within a repository alone or **invite others to collaborate with you on those files**. You can find an example of a repository [here](https://github.com/g-pacheco/FeralPigeonGenomics). Take some time to navigate through and get yourself familiarised. 

### Cloning 

When a _repository_ is created with _GitHub_, it is stored remotely in Narnia (aka The ☁️). You can clone a _repository_ to create a local copy on your computer (your Precious!) and then use _Git_ to sync the two. This makes it easier to fix issues add/or remove files as well as add larger commits (your comments on specific changes your have made). You can also use the editing tool of your choice (like _VSC_) as opposed to the _GitHub User Interface_ (this page you are looking at right now). Cloning a repository also pulls down all the repository data that _GitHub_ has at that point in time, including all versions of every file and folder for the project! This can be helpful if you experiment with your project **and then realize you liked a previous version more**. To learn more about cloning, read ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Committing & Pushing

**Committing** & **Pushing** are how you can add the changes you made on your local machine to the remote repository in _GitHub_. That way your peer scientists can see your latest work when you are ready to share it. You can make a commit when you have made changes to your project that you want to _checkpoint_. You can also add a helpful _commit message_ to remind yourself or your teammates what work you did (e.g. “I changed the colour of the samples' names.”).

Once you have a commit or multiple commits that you are ready to add to your repository, you can use the push command to add those changes to your remote repository. Committing and pushing may feel odd at first, but I promise you will get used to it 🙂
***

### Using _Markdown_ on GitHub 

_GitHub_ uses a super simple language called Markdown. If you are not familiarised with it, you can have a good idea of how it works [here](https://guides.github.com/features/mastering-markdown/). To learn more about using _GitHub_’s flavor of markdown, please read ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Forks

A fork is another way to copy a repository, but is usually used when you want to contribute to someone else’s project. Forking a repository allows you to freely experiment with changes without affecting the original project and is very popular when contributing to open source software projects!
To learn more about forking, read ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Your user profile

Your profile page tells people the story of your work through the repositories you are interested in, the contributions you have made, and the conversations you have had. You can also give the world a unique view into who you are with your profile README. You can use your profile to let other researchers know all about you! 
To learn more about your user profile and adding and updating your profile README, read ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

#### Hands-On

### Initial _Git_/_GitHub_ SetUp

- Please open _Git Bash_ and type the following commands:

```
git config --global user.name "YOUR-USERNAME"
```

```
git config --global user.email "YOUR-EMAIL"
```

There are loads of more advance configurations, and you can check them [here](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration). However, having these two should get you going. Your can check that everything went through with the command below:

```
git config --list
```

### Creating A Repository & More

Alrigh -- I believe you all set and now you just follow what I will be presenting on the screen. Some of the command we will be using are shown below, but I reckon that it will be straightforward to you to imitate what I will be doing.

  
```
git add .
```

```
git commit -m "YOUR-COMMIT"
```

```
git push
```
#

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
