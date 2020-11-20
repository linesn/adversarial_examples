# adversarial_examples
A project exploring the use of adversarial examples to defeat classifiers. This project was made as part of Johns Hopkins EN.625.638 Neural Networks course, by students Daniel Donoghue, Nicholas Lines, and Arnaldo Pereira, under the direction of Professor Mark Fleischer.

# Project goals
For background on adversarial machine learning, our goals for this project, and other details, refer to [our project proposal](Project_Proposal_Adversarial_Examples.pdf).

# How to contribute while we make this project
Before getting started, be aware that the initial git clone will take a long time. You'll need to clone to a drive that has at least 500 MB free. 
* In the spirit of reproducible research, following the example of [The Turing Way](https://the-turing-way.netlify.app/reproducible-research/renv.html) we'll use git and conda as our version control and environment management tools. To set up your environment, first clone this repository on your machine. Then within this top-level directory install and activate the project's conda environment with 
```Bash
conda env create -f conda.yaml
conda activate ae
```
* We are including the data in this github, which is bad form. If anyone has a better idea how to share that data, let me know and we can wipe it out of the repo. 
* When you make changes to the code, use git commits to track your work.
* Because git is weird about notebook output, unless there is a reason to preserve it, clear your cell outputs before committing a notebook.
* When you need to install new packages for the project, wherever possible use `conda install` to get them, and then update the project's conda environment with 
```Bash
conda env export > conda.yaml
```
