# Setting up a Professional Data Science Environment - Installation

## Introduction
If you want to become a professional data scientist, it’s important to take a little time to “set yourself up for success” by installing and learning to use the right tools on your computer. In this lesson, you will install Git and Anaconda and in the next lesson you will setup a virtual environment. If you already have Git and Anaconda installed, feel free to skip to the next lesson to get started with cloning, virtual environment setup, and testing!

## Objectives
You will be able to:
* Install Git
* Install Anaconda

## What Tools do Professional Data Scientists Use?

- **Python** - There are many languages that can be used for data science, but these days most data scientists are using Python to write their code.
- **Jupyter Notebook** - Most of those data scientists use Jupyter Notebook for writing their Python code. Jupyter Notebook is a tool that allows you to mix comments in-between your code snippets so you can document and share your thought process and make it easier for others to review, replicate, and expand on your work. It's also what we're using for almost all of our lessons in this course!
- **Anaconda** - Anaconda is one of the most popular ways for data scientists to install Python and Jupyter on their computers. It also provides package management and virtual environments so you can get all the latest data science tools running, like NumPy, SciPy, and Tensorflow, and so you can use different versions of Python and your packages for different projects without them conflicting with each other.
- **Git** - Git is a version control system. It’s a way of keeping track of all the changes made across your project. Think of it like “track changes” in Word - but with the ability to track changes across multiple documents. At Flatiron School, we use Git to keep track of all of the lessons we create and all the changes we make to them.
- **GitHub** - GitHub is a website where data scientists (and programmers) can save their work in case their computer breaks, and share it with their team or the world! At Flatiron School, we store all of our lessons on GitHub.

It’s going to take us a few minutes to get this all installed, but once we do, not only will you be set-up for working through the course, but you’ll also have a professional data science setup on your computer for any future courses or projects you want to work on!

## Computer Prerequisites

There are many amazing computing devices available these days, but not all of them will allow you to do data science. We love smartphones, flip phones, Chromebooks, tablets (including iPads), game boys, Nintendo switches, roku’s and arduino’s. You’re not going to be able to complete this course on any of those devices - sorry.

You’re going to need a computer (laptop or desktop). It should be running a recent (last 3-4 years) version of MacOS, Windows or Linux, and ideally, it should have 8Gb of RAM and at least 20Gb free hard drive space. More information [here](https://flatironschool.com/wp-content/uploads/Student-Facing-Computer-Requirements.pdf):

Assuming you have a computer that meets the requirements, let’s start by getting Git and Anaconda installed.

For each tool, we’ll provide installation instructions for the two most common operating systems - Windows and MacOS.

Please note - the exact names and versions will change over time.

## Installing Git

### Installing Git on Windows

Overview: 

1. Download the install package from [here](https://git-scm.com/download/win)
2. Double click to open the downloaded exe file
    - It may open a window asking if you want to allow this application to make changes to your device, click “Yes”
3. Click “Next” to accept the license
4. Select Components on the next screen - make sure to keep the “Windows Explorer integration” options checked *
5. Choose a default editor that you are comfortable with, or choose either Nano or Visual Studio Code if you have not used an editor before
    - If you know or have used vi/vim, feel free to use it (otherwise it is not recommended)
6. Adjust your PATH environment - select “Use Git from the Windows Command Prompt”
    - The first option is also fine, as you’ll mainly be using Git from the new “Git Bash” program that is being installed, but the second option is ideal as it’ll give you the option of using it through either Git Bash or the Windows Command Prompt in the future if you wish
7. Choose HTTPS transport backend- select the “Use the OpenSSL library” option
8. Configure line-ending conversions - select the default option for handling line endings
9. Use MinTTY as the default terminal emulator
10. Configure extra options to enable file system caching and the git credential manager
11. Wait while Git is installed onto your computer
12. Click "Finish" to complete set-up


\* It is **strongly suggested** that you select any options to install and use the "Git Bash" shell - it's generally included by default. The Git Bash shell will allow students with either Windows or Mac computers to run the same set of commands.

Note - if there are any differences in the options provided in the installer you download, accept the defaults.

#### Git Installation Steps for Windows, step-by-step:

Step 4 - Select components: 

![screen-1](http://curriculum-content.s3.amazonaws.com/data-science/screen-1.png)

Step 5 - Choose a default editor:

![screen-2](http://curriculum-content.s3.amazonaws.com/data-science/screen-2.png)

Step 6 - Adjust your PATH environment

![screen-0](http://curriculum-content.s3.amazonaws.com/data-science/screen-0.png)

Step 7 - Choose HTTPS transport backend

![screen-3](http://curriculum-content.s3.amazonaws.com/data-science/screen-3.png)

Step 8 - Configure line-ending conversions

![screen-4](http://curriculum-content.s3.amazonaws.com/data-science/screen-4.png)

Step 9 - Configure the terminal emulator to use with Git Bash

![screen-5](http://curriculum-content.s3.amazonaws.com/data-science/screen-5.png)

Step 10 - Configure extra options

![screen-6](http://curriculum-content.s3.amazonaws.com/data-science/screen-6.png)

Step 11 - Installation

![screen-7](http://curriculum-content.s3.amazonaws.com/data-science/screen-7.png)

Step 12 - Complete!

![screen-8](http://curriculum-content.s3.amazonaws.com/data-science/screen-8.png)

### Installing Git on Mac

If you are comfortable with the command line and have installed [homebrew](https://brew.sh/), you should install Git by running the command `brew install git` in a terminal window. If you have no idea what the last sentence meant, please disregard and follow the below steps.

Overview:

1. Download the install package from [here](https://git-scm.com/download/mac). 
2. Double click on the downloaded dmg file to open a small Finder window
3. Double click on the .pkg file to run it
    - When you try to do that you might get a security warning pop up. If that happens: 
        - Click on the apple at the top left of the screen
        - Select “System Preferences” from the drop-down menu
        - Select “Security and Privacy”
        - Select the “General” tag
        - Click on the lock to make changes at the bottom of the window (you will need to enter your password when prompted)
        - Below the “Allow apps downloaded from” option, you should see a message stating that an app was blocked from opening (if you don’t see this message, double click on the .pkg file again and then look back at the Security & Privacy screen and it should pop up). Click the “open anyway” button.
4. Click on the “Open” button when the pop-up message asks "Are you sure you want to open it?" in order to open the installer window
5. Click "Continue" on each screen, then "Install"
    - You will need to enter your password when prompted
6. When the installation is complete, click the "Close" button

#### Git Installation Steps for Mac, step-by-step:

Step 2 - Finder window that appears when you double click the downloaded dmg file

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-10.png' width="750">

Step 3 - Security warning that may appear

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-11.png' width="550">

Step 4 - Yes, you really want to open the app

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-12.png' width="550">

Step 5 - Installer screen

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-13.png' width="650">

Step 6 - Click "Close" when the Installation is completed successfully

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-14.png' width="650">


## Confirming Your Git Installation (All Operating Systems)

To confirm you have installed Git successfully:

1. Open a terminal window

    - On Windows, using the start menu, open the “Git Bash” program to open a terminal window
    - On a Mac, open the “Terminal” app in the “Utilities” folder within your “Applications” folder - or, find the "Terminal" app in your Launchpad 

2. Type `git --version`: It should return the version of git you are running

While you’re in the terminal, you should also set up your name and email address:

1. In your terminal window, type `git config --global user.name`

    - If it returns your name, you’re set! 

2. If it returns nothing or displays an error message, type `git config --global user.name “Your Name”` - replacing Your Name with your name inside the quotes

3. Type `git config --global user.email`

    - If it returns your email address, you’re set! 

4. If it returns nothing or displays an error message, type `git config --global user.email your@email.com` - replacing your@email.com with your email address

## Installing Anaconda 

The easiest way to get set up with Python and Jupyter Notebook so you can start coding is to install the Anaconda distribution. 

### Installing Anaconda on Windows

Overview:

1. Download the latest version of Anaconda [here](https://www.anaconda.com/download/#windows) - use Python 3.x (ignore Python 2.7)

    - A window may pop up asking if you want to give Anaconda your information in return for a cheat sheet - you do not need to do so unless you want to

2. Open the exe file once it has downloaded to open the Anaconda installer

    - Option 1: When the exe file is finished downloading, click the arrow to the right of the name of the file at the bottom of your browser, and select "Open"
    - Option 2: Navigate to your "Downloads" folder and double click on the Anaconda exe file to open it

3. Click "Next", then "I agree" to accept the license
4. Install for "Just me" and click "Next"
5. Select the destination folder - it is recommended that you stick with the default destination
6. Choose both Advanced Installation Options - although you will see a warning from the installer, **_make sure_** to choose "Add Anaconda to my PATH environment" !!
7. Wait while Anaconda is installed on your computer
8. When the Anaconda installation is complete, click "Next"

    - You can skip the Visual Studio Code installation

9. When it thanks you for installing Anaconda, click "Finish"
    - You do not need to learn more about your installation, and can close the browser window if it opens

#### Anaconda Installation Steps for Windows, step-by-step:

Step 1 - Download Anaconda for Python 3.x

![screen-15](http://curriculum-content.s3.amazonaws.com/data-science/screen-15.png)

Step 2 Option 1 - Open the exe file from the browser

![screen-16](http://curriculum-content.s3.amazonaws.com/data-science/screen-16.png)

Step 2 Option 2 - Open the exe file from your Downloads folder

![screen-17](http://curriculum-content.s3.amazonaws.com/data-science/screen-17.png)

Step 3 - Continue through the Anaconda installer

![screen-18](http://curriculum-content.s3.amazonaws.com/data-science/screen-18.png)

Step 5 - Choose install location

![screen-19](http://curriculum-content.s3.amazonaws.com/data-science/screen-19.png)

Step 6 - Advanced Installation Options: **make sure to check the "Add Anaconda to my PATH environment" checkbox**

![screen-20](http://curriculum-content.s3.amazonaws.com/data-science/screen-00.png)

Step 7 - Installing Anaconda

![screen-21](http://curriculum-content.s3.amazonaws.com/data-science/screen-21.png)

Step 8 - Completing the install

![screen-22](http://curriculum-content.s3.amazonaws.com/data-science/screen-22.png)

You can skip the Visual Studio Code installation

![screen-23](http://curriculum-content.s3.amazonaws.com/data-science/screen-23.png)

Step 9 - Finish the install

![screen-24](http://curriculum-content.s3.amazonaws.com/data-science/screen-24.png)

You can close any browser window opens to an Anaconda page

![screen-25](http://curriculum-content.s3.amazonaws.com/data-science/screen-25.png)


### Installing Anaconda on Mac

Overview: 

1. Download the latest version of Anaconda [here](https://www.anaconda.com/download/#macos) - use Python 3.x (ignore Python 2.7)
2. Open the pkg file once it has downloaded to open the Anaconda installer

    - Option 1: When the pkg file is finished downloading, click to the right of the name of the file at the bottom of your browser, and select "Open"
    - Option 2: Navigate to your "Downloads" folder and double click on the Anaconda pkg file to open it

3. Click "Continue" to run the package to determine if the software can be installed
4. When the Installation window opens, click "Continue"
5. Look at the Read Me, then click "Continue"
6. Accept the license by clicking "Continue", then click "Agree" in the pop-up window
7. Accept the default destination
8. Click "Install" to install the software
    - You will need to enter your password when prompted
9. Wait while Anaconda is installed on your computer
10. You can skip the option to install Microsoft VSCode by clicking "Continue"
11. Click "Close" when the installation was completed successfully
12. If you're asked whether you'd like to move the Installer to Trash, click "Move to Trash"

#### Anaconda Installation Steps for Mac, step-by-step:

Step 1 - Download Anaconda for Python 3.x

![screen-26](http://curriculum-content.s3.amazonaws.com/data-science/screen-26.png)

Step 2 Option 1 - Open the pkg file from the browser

![screen-27](http://curriculum-content.s3.amazonaws.com/data-science/screen-27.png)

Step 2 Option 2 - Open the pkg file from your "Downloads" folder

![screen-28](http://curriculum-content.s3.amazonaws.com/data-science/screen-28.png)

Step 3 - Determine if the software can be installed

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-29.png' width="600">

Step 4 - Anaconda Installer

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-30.png' width="600">

Step 5 - Accept the Read Me

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-31.png' width="600">

Step 6 - Accept the License

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-32.png' width="600">

Click "Agree" in the pop-up window

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-33.png' width="600">

Step 8 - Install

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-34.png' width="600">

You may need to enter your password

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-35.png' width="600">

Step 9 - Installing Anaconda

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-36.png' width="600">

Step 10 - You do not have to install Microsoft VSCode

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-37.png' width="600">

Step 11 - Completing the install

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-38.png' width="600">

Step 12 - Move Installer to Trash

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-39.png' width="600">

## Testing Your Anaconda Installation (All Operating Systems)

To test your installation:

- On Windows, click on Start and then Anaconda Navigator in the program list (or search for Anaconda in the search bar and select Anaconda Navigator)
- On a Mac, open up the finder, and in the Applications folder, double click on Anaconda-Navigator

From now on, screenshots will be from a Mac, but we’ll highlight any material differences in the experience between the operating systems.

The Anaconda Navigator is one of the ways you’ll be able to run Jupyter Notebooks. Click on the “launch” button in the Jupyter notebook tile.

![screen-40](http://curriculum-content.s3.amazonaws.com/data-science/screen-40.png)

On a Mac, you’ll see a terminal window pop up.

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-41.png' width="600">

On both Windows and a Mac, you’ll see a window in your web browser that allows you to open existing Jupyter notebooks or create a new one.

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-42.png' width="1000">

Click on the “New” button in the top right corner.

![screen-43](http://curriculum-content.s3.amazonaws.com/data-science/screen-44.png)

And select “Python 3” from the drop-down list.

When you do, you’ll see a new notebook in your browser window that looks something like this:

<img src='./images/new_notebook.png' width="650">

To make sure it’s working, click in the cell and type the following:

```
import sys
print(sys.version)
```

Then hold down the shift key and hit return/enter (`shift`+`return`) to run the code in the cell. You should see an output something like this:

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-43.png' width="650">

Don’t worry if the version number or date is slightly different. If you get a similar output (something that isn’t an error message), congratulations! You’ve got Anaconda, Python and the Jupyter notebook installed successfully!

To shut down Jupyter notebook, just close the tabs in your browser containing the notebook and the list of notebooks. On a Mac, you should also click on the terminal window, hold down the control key and hit C (`control`+`C`) to close the notebook.

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-45.png' width="600">

You’ll then have to hit “y” and return/enter to confirm that you want to close down Jupyter notebook.

<img src='http://curriculum-content.s3.amazonaws.com/data-science/screen-46.png' width="600">

## Summary

Congratulations! If you've gotten this far and everything has worked, you have successfully installed Git and Anaconda on your computer! Next, you'll learn what a virtual environment is - and set one up!
