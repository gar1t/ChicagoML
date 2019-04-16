---
title: Pull Requests
layout: default
nav_exclude: true
---

# Pull Requests

This is a guide to submitting changes to this site via pull requests.

For general information about pull requests, see [About pull
requests](https://help.github.com/en/articles/about-pull-requests) on
GitHub help.

## Step 1 - Fork Chicago ML repository

Visit
[https://github.com/gar1t/ChicagoML](https://github.com/gar1t/ChicagoML)
and click **Fork** in the upper right corner.

![](/assets/images/fork.png)

If prompted, select the account you want to create the fork in.

Note the URL of your forked repository.

![](/assets/images/clone.png)

## Step 2 - Clone your forked repository

From a command line (or other Git interface), run:

``` bash
git clone URL_OF_YOUR_REPO
```

where `URL_OF_YOUR_REPO` is the URL from Step 1.

## Step 3 - Make changes to your cloned repository

Make whatever changes you want to submit as a pull request.

Commit you changes:

``` bash
git commit
```

Type a commit message that describes your changes.

We recommend reading [Commit Message
Guidelines](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53)
for general guidelines on writing messages.

Push your changes:

```
git push
```

## Step 4 - Submit pull request

Visit you repository on GitHub and refresh the page. You changes
should be reflected on the page as "This branch is N commit(s) ahead
of gar1t:master".

Click **Pull Request**:

![](/assets/images/pr.png)

And then **Create pull request**:

![](/assets/images/create-pr.png)

Review the pull request and then click **Create pull request** again:

![](/assets/images/create-pr-2.png)

## Step 5 - Look for merge notice

We will require your contribution and merge it provided it meets our
[Contribution Policy](/contributing/).

And thank you for your contribution!
