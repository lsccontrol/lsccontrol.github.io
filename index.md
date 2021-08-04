---
layout: default
---

# LSCBot

LSCBot is a service that saves precious developer time by performing codebase maintenance tasks on a global scale.

*(LSC stands for **Large Scale Change**).*


## How it works
The LSCBot team, with the help of the community, is continuously adding new LSCs that are applied by LSCBot to all registered repositories.

When a new LSC is added, LSCBot scans the list of registered public and private repositories to detect which are affected by the change.

LSCBot sends a PR to each affected repository with the suggested fix.

The repository owner can review the change and merge it.

## I want LSCBot's help in maintaining my repository!
Register your repository here to make sure LSCBot is monitoring it for available maintenance tasks:


<a id="register" href="/register">Register</a>


## The Economics of LSCBot
All codebases require constant maintenance.

Following a deprecation in a library for example, all affected developers need to understand how to migrate their codebase and apply the change.

Looking at the code maintenance work on a global scale, for many changes it is much more efficient to have a single small team become experts in the migration and apply it to all projects. So instead of having a thousand engineers spend 2 hours each, we end up with 2 engineers spending a week and fixing all thousand projects that need to be fixed.

Furthermore the larger the scale of the change the more it makes sense to invest in automation.

LSCBot serves as a central hub for performing code base maintenance across the entire software ecosystem.

## Who’s getting access to my private repository?
For LSCs that are fully automated you can set up a cron job that routinely applies available LSCs and sends a PR from an account you own - this way LSCBot does need any access to your code.

However not all LSCs are fully automated, for non-fully automated LSCs LSCBot will let you know that an LSC is available for your repository and will ask you for temporary access to your repository in order to perform the refactoring. You can choose to manually approve each request, or automatically allow/deny all requests.


## How do I create a new LSC?

We encourage developers and libary authors to use LSCBot to apply refactorings across the global code base!

We'd love to walk you through the process of creating a new LSC! Please reach out to <new-lsc@lscbot.com>.
