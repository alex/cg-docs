---
menu:
  main:
    parent: apps
title: General Deployment Tips
weight: 10
---

## Twelve-Factor Apps

In general, applications will be easiest to deploy to Cloud Foundry if they follow the [Twelve Factor App](http://12factor.net/) guidelines.

## Exclude files

In most cases, you will want to [exclude files](http://docs.cloudfoundry.org/devguide/deploy-apps/prepare-to-deploy.html#exclude) ignored by Git. From within your project directory, run

```bash
ln -s .gitignore .cfignore
```

and commit the `.cfignore` to your repository.