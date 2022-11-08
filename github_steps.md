# GitHub Steps

To connect a cloud repository from GitHub to your local computer follow these steps:
1. Fork the repository
1. Copy the SSH code key
1. Nvaigate to the directory you would like the new repository in
1. Type `git clone <SSH code key>` 

To connect a local repository to a cloud repository on GitHub follow these steps:
1. Create a new directory in the location you would like
1. Initialize Git with `git init`
1. Create at least one file
1. Add and commit your file with `git add .` and `git commit -m "Initial commit"`
1. Create a new repository on GitHub (it helps to name it the same as your directory)
1. Ensure SSH is clicked
1. Copy the three lines of code from GitHub and paste them into terminal