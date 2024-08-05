# codespaces-wiki

This readme describes how to setup codespaces with your repository.

## Github user in organisation

At this point you should have github user set up in github organisation.

![Github organisation](/images/github-organisation.png)

## Create code repository in Github

Think of how your project will be called and name repository the same way.

It can be *dasherized-styled-naming*, it can be *underscored_styled_naming*.

Maybe it makes sense to prefix projects with some initials like isk-cool-quiz, if my name is **I**ngus **Sk**aistkalns

Avoid generic naming as *test-project*, *my-project*, *example-project*

![Create repository](/images/create-repository.png)

## Create codespaces

Create codespaces in github

![Create codespaces](/images/create-codespaces.png)

Select your created repository you want to work with

![Select repository](/images/select-repository.png)

Select Europe region and weakest instance type.

## Access codespaces in Github

Under your profile codespaces you should be able to see your created codespaces

![Access codespaces](/images/access-codespaces.png)

![Codespaces list](/images/codespaces-list.png)

## Turn codespaces off after work

To save up some VCPU minutes, dont forget to turn codespaces off
after you have finished your work session.

![Stop codespaces](/images/stop-codespaces.png)

## Install Microsoft VS Code

Grab the installations and set up [Miscrosoft VS Code](https://code.visualstudio.com/download)

## Start codespaces 

Start codespaces with opening in Microsoft VS Code

![Start codespaces](/images/open-codespaces-in-vs-code.png)

Allow extension to open URI!

![Allow extension](/images/allow-extension.png)

Sign into github

![Sign in](/images/sign-into-github.png)

Manage trusted extensions and select Github Codespaces & Github & Github Pull Requests

![Manage trusted extensions](/images/manage-trusted-extensions.png)

Wait while codespaces gets loaded and you are ready to go!

![Codespaces loaded](/images/codespaces-loaded.png)

## There are controls inside

![Controls in VS](/images/controls-in-vs.png)

## Ruby, Rails & git commit

From Microsoft VS Codes terminal run commands:

```bash
$ ruby -v
$ gem install rails
$ rails new . --name={your-project-name-goes-here} --database=sqlite3
```

```bash
$ cd {your-project-name-goes-here}
$ git add .
$ git commit -m "Initialize rails app"
$ git push
```