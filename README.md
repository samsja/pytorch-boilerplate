# Boilerplate code for pytorch lightning project to dev with jupyter lab and docker

this boilerplat create a project with the following things:

* pytorch lightnings 
* poetry manage the dependencies
* jupyter lab
* add a dockerfile if needed to either develop or run a script
* use precommit hook for auto formatting before commiting
* use jupytext sync to avoid to commit notebook


This is my personnal boilerplate to avoid copy pasting the same code at each new deep learning project. Feel free to use it, creat an issue, forked it and send a PR !

## How to use it ?:

install first cookiecutter

```shell
pip install cookiecutter
```

then simply run

```
cookicutter https://github.com/samsja/pytorch-boilerplate
```

