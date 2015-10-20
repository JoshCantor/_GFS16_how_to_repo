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

