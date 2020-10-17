# Empirical Research Python Lab

## Contacts

marco.saletta@gmail.com

## Prerequisites

The course will be focused on an introduction to Python with focus to data analysis and machine learning.

The two main tolls will be:
  - **Jupyter:** interactive notebook for Python and others language
  - **Git:** repository system [wiki page](https://en.wikipedia.org/wiki/Git)

### Install git

  - **For Window user:** download git from https://gitforwindows.org/. During the installation select **use git bash only** in the relative step, leave the rest like it is.
  - **For Unix/Mac users:** git should be already available in the terminal.

I invite you to create and account on [GitHub](https://github.com/) or [GitLab](https://gitlab.com/users/sign_in) and start to using it following some guide like:
  - http://kbroman.org/github_tutorial/pages/init.html
  - http://rogerdudler.github.io/git-guide/

### Install Anaconda

One the easiest way to have Python and Jupyter is via Anaconda.

From the site download the version for **Python 3.7**:

https://www.anaconda.com/download/

After the installation of the tool, you have to create a dedicated environment with all the packages that we will use in the course.

**Note** I strongly recommend you to create a dedicated environment even if you already have Anaconda or Python on your PC. In this way you can avoid to mess up the packages between what we need and what you already have. In general, it's always a good idea to have a dedicated environment for each project.

In order to create the environment, follow the steps listed below:

  1. Open Anaconda Navigator
  2. Click on _Environments_ on the left panel
  3. Click _Create_ at the bottom of the page
  4. Write _Cattolica2020_ as _Name_ in the pop up window
  5. Select **Python 3.7** as version
  6. Click create

![alt text](./images/CreateEnv.png "Create Environment")

After those steps, we need to install the packages that we need. In order to do that follow again this steps:

  1. Select _Envirements_
  2. Check that _Cattolica2020_ is the selected environment
  3. Change form _installed_ to _all_ in the drop down menu on the top left
  4. Search and than select the following packages:
    * Pandas
    * Tensorflow
    * Scikit-learn
  5. Click _Apply_

![alt text](./images/Packages.png "Packages Selection")

**Note**: The installation could take some time.

After the installation, as last step, return in _Home_ and install _Jupyter Notebook_ (or _Jupyter Lab_, but we'll use the first).

If you are confuse about the procedure ask during the first lesson, we follow it together.

You can find a guide for Jupyter here: [Jupyter Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook).


### How to clone the repository for one/all the lessons

All the files of each lesson will be in a dedicated repository on my [GitHub page](https://github.com/SalMarco).

Each repository will be named *Cattolica_2020_Lesson#*, where *#* is the number of the lesson.

For example the repository for the *Lesson1* is [here](https://github.com/SalMarco/Cattolica_2020_Lesson1).

For each lesson, in order to bring the files on your PC, you have to **clone** the repository.

In order to do that you have to use the terminal. If you are a Mac/Linux user you can find it right away, while for Windows' users you have to open _Git Bash_. You have installed it in the first step of the Prerequisites.

You can find some basic information and commands about the terminal in the following sections.

**Note**: you can also simply download the repo, but I strongly advice you to use the terminal and the _clone_ procedure.

Do not be afraid if this is your first experience using git. You will have to use it as soon as you'll start to work, so why not start now?

We'll also see how to use it during our lessons.

### Terminal 101

#### Open the terminal

For **Mac/Linux** just open the terminal

For **Windows** start `git bash`.  

In order to get familiar with the terminal, you can use [this page](https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je).

The most important sections for us are:

  - Navigating Filesystem
  - Creating and Deleting Files and Directories

#### Select a destination for the repository

You can see the path of the folder you are in with `pwd` (i.e. print working dir). At the beginning you should be in your home folder.

You can list all the files/folder with `ls -lrt`. The most recent files/folders will be at the bottom.

You can change the directory you are in with `cd $folderName`.

If you use only `cd` you will return to your home folder.

With `cd ..` you will return **one** step back in the folders tree.

Execute the commands as you need and put yourself in the folder inside you want to create the new folder for the repo.

Again, if it's your first experience with a terminal do not be afraid. We will se how to use it during the lectures.

#### Clone the repo

The command to clone a repository is `git clone ....`, where _...._ must be replaced with the pointer of the repository.

You can find the pointer from the green button _Code_ in the GitHub page. Select _Https_ ad copy the link.

![alt text](./images/CloneRepo.png "Clone Button")

For example, order to clone the `Cattolica_2020_Lesson1` repository with all its files execute

`git clone  https://github.com/SalMarco/Cattolica_2020_Lesson1.git`

Enter inside the folder that has been created and use `ls -lrt` to see all ther files.
