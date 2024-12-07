# dataverse.org (Hugo)

This GitHub project hosts the sources from which the Dataverse website at https://hugo.dataverse.org is built.
If we like Hugo, we might switch https://dataverse.org to it.
Builds are automated and any committed changes will be released by automation.

If we like Hugo, we might switch https://dataverse.org to it.

You can make small edits using the GitHub web editor by changing Markdown files.
For larger changes, we recommend working with a local setup, which also allows you to preview your changes.
See below for a tutorial.

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
