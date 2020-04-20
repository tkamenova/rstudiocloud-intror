
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Get started

## Fork this repo

1.  Create an account on github
2.  Navigate to
    [lockedata/rstudiocloud-master](https://github.com/lockedata/rstudiocloud-master)
3.  Hit the fork button and select your account

## Clone this repo

1.  Make sure you have git locally
2.  Configure git with your info via the terminal

<!-- end list -->

    git config --global user.name "Jane Doe"
    git config --global user.email janedoe@example.com

3.  Time permitting, and your personal devices, perform [SSH key set
    up](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)
4.  In RStudio, select New Project from Source Control, then selct Git
    and paste in the URL of your forked version of this repository

([@cthydng](https://twitter.com/cthydng/status/575483540202106880))
![git model](https://lockedata.co.uk/introrbio/img/Github-flow.png)

## Install packages

This repo has a DESCRIPTION file containing our recommended packages.

1.  Run `install.packages("remotes")` if you do not already have it
    installed
2.  Run `remotes::install_deps(dependencies=TRUE)` to install all the
    desired packages
