# Git Cheatsheet

### Start a new project

```shell
$ mdkir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "message"
```

### Do some work and then save it

First, do some work in a file that's already in the repo!

```shell
$ git status
$ git add <whatever_file>
$ git status
$ git commit -m"I made some changes"
```

### Share my work with the world

First, creat a github repo

```shell
$ git remote add origin git@github.com:<github_user_name>/<name_of_repo_on_github>.git
$ git push -u origin master
```

### Help someone else with their code

First, find the code on github that I want to contribute to.

```shell
$ *navigate to directory I want the repo in
$ git clone git@github.com:<my_user_name>/<name_of_repo_on_github>.git
```
Then, make some changes you think are importants

```shell
$ git add <my_updated_file>
$ git commit -m "Thorough explanation of what I changed"
$ git push origin <branch>
```

Finish what you started woring on, then push up any additional commits.

File a pull request with the commits you want to share. Make sure it has a good explanation.


