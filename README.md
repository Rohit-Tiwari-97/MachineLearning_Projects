## Starting a Machine Learning Project

### Software and account Requirement:-

1. [Github Account](https://github.com/)
2. [Heroku Account](https://id.heroku.com/login)
3. [VSCode IDE](https://code.visualstudio.com/download)
4. [Github CLI](https://git-scm.com/downloads)
5. [Github Documentation](https://git-scm.com/docs/gittutorial)

### Creating Conda Enviroment

1. Checking conda installed or not
```
conda --version 
```
2. Create Virtual Enviroment
```
conda create -p venv python==3.9.7 -y
```
3. Activate the enviroment
```
Conda activate vnv OR Conda activate vnv/
```
OR
```
conda activate D:\FSDS_2021_Ineuron\Projects\MachineLearning_Projects\venv
```
4. Install the required libraries
```
pip install -r requirements.txt
```
5. To check which files we have not added in the github repo(status)
```
git status
```
6. To add File in github
```
git add <file_name> OR git add .(for all files)
```
7. To create a version
```
git commit -m "mesaage"
```
8. To see the previous commits/versions
```
git log
```
9. To send all the files on github
```
git push origin main
```
10. To check all branches in git
```
git branch
```
> Note: to ignore file or folder from git we can write name of file/folder in .gitignore file