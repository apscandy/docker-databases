# Use full docker database images

This repo is used as a git submodule target to add databases to repos that need a database when writing software.

```sh 
git submodule add https://github.com/apscandy/docker-databases.git

```

if the remote repo (this one) is updated and you would like the new submodule changes run the following command
```sh
git submodule update --remote 
```
