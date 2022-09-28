# Getting started

This repository is made for Big data platforms 2022 course from Helsinki´s open university. All course material is owned by Helsinki university. All code development is made by owner of this repository **Miika Mikkonen**.

Code can be cloned to your local workstation by `git clone <<REPOSITORY_URL>>` and to use the repository files
- Open your terminal/kernel
- Move to the exercise folder
- open the environment by using jupyter notebook with command `jupyter notebook`

## Prequisites

**Environment needs:** 
- Python 3.10.* version
- Jupyter notebook
- Spark
- Numpy
- Matplotlib

Development can be done via course virtual machine which is available from the course files. The virtual machine has all dependencies installed. Other way is to install the necessary tools to local development station and use python virtual environments. Enviroment manager can be also used e.g. Anaconda.

# Development

Development is done by using branching. Developing a course part will have to match a separate branch.
When course part is ready the branch can be merged to the main branch.

Creating a new branch from the command line
- `git branch <<BRANCH_NAME>>`
	- Creating a branch locally
- `git checkout <<BRANCH_NAME>>`
	- Moving to the branch locally
-  `git add . && git commit -m "comment"`
	-  Doing changes and adding files to the commit history for the local branch
- `git push --set-upstream origin <<BRANCH_NAME>>`
	- Pushes changes to a new branch to the version control