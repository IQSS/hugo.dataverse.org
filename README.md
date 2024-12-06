# dataverse.org (Hugo)

This GitHub project hosts the sources from which the Dataverse website at https://hugo.dataverse.org will be built.

Next, we'll be following https://gohugo.io/hosting-and-deployment/hosting-on-github/

If we like Hugo, we might switch https://dataverse.org to it.

## Prepare your environment

Install Hugo from https://gohugo.io

## Get the source code

Next, you need to obtain a version of the website "source code". Here are the commands for cloning the git repo, entering that directory, and downloading submodules:

```shell
git clone https://github.com/IQSS/hugo.dataverse.org.git
cd hugo.dataverse.org
git submodule init
git submodule update
```

## Build the website for preview

```shell
hugo serve
```

Go to http://localhost:1313
