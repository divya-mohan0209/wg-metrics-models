# How to Contribute

## Where can I contribute?

Anyone can contribute to CHAOSS on any of our communication channels. See <https://chaoss.community/participate/>.

**Every issue in this repository is seeking contribution**. Click on issues to find ways to contribute. See this [list of all issues](https://github.com/chaoss/wg-value/issues).

### We need activists, enthusiasts, community input, and more. Anyone, with any skill set, can find a way to pitch in.

## Contributing to the Chaoss Community

Thank you for your interest in contributing :tada:!

This document outlines a process of contributing.

## How to submit changes

Once you've identified one of the issues above that you feel you can contribute to, you're ready to make a change to the project repository!

1. **[Fork](https://help.github.com/articles/fork-a-repo/) this repository**. This makes your own version of this project you can edit and use.

```

    Example:

    git clone git@github.com:<your-username>/<repository>.git
    
```

2. **[Create a Branch](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)**. If you already have the repo, please be sure that you have upstream merged into your master branch. And then create the branch. There is some [info](https://help.github.com/articles/syncing-a-fork) available at about syncing repositories.

```

    Example:

    git checkout -b <branch>

```

3. **[Make your changes](https://guides.github.com/activities/forking/#making-changes)**! You can do this in the GitHub interface on your own local machine. Once you're happy with your changes. If there are a bunch of commits and those are adding things, fixing a couple of typos, etc, please consider merging some of those into a smaller set of commits. This helps to review the whole process. More [info](https://blog.carbonfive.com/2017/08/28/always-squash-and-rebase-your-git-commits/).

Make your change and commit the change (NOTE: with `-s` you sign-off on each commit, which is your [Developer Certificate of Origin](https://developercertificate.org/)):

```

    Example:

    git add <changed file>
    git commit -s -m "<description of change>"

```

*If you forget to add the sign-off you can also amend a previous commit with the sign-off by running `git commit --amend -s`. If you have pushed your changes to GitHub already you'll need to force push your branch after this with `git push -f`.*

If this step sounds a bit difficult, the maintainers of the repository can help with this process when merging the PR.

3. **Submit a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests)**. This opens a discussion around your changes and lets the project lead know you are proposing changes.

```

    Example:

    git push origin <branch>

```

4. **[Document Commit](https://medium.com/@steveamaza/how-to-write-a-proper-git-commit-message-e028865e5791)** Start the sentences with a capital letter, write a short sentence (usually no more than ~70 characters) and use that as you use the subject of an email.
    If you want to add more information, leave a blank line
    And then start the paragraph you want to write down (please remember the limitation of 70 characters).
   
First time contributing to open source? Check out this Blog, [Best practices in a collaborative environment](https://channelcs.github.io/best-practices-in-a-collaborative-environment.html).

5. **References** Please include links to resources elsewhere that may be helpful to others. Include the references inside the files you are editing. This is not a hard requirement, but we encourage you to provide references if you know what source informed your contribution.

## How to report bugs

Notice a mistake? Please file any bugs, requests, or questions in [our issue tracker](https://github.com/CHAOSS/wg-value/issues)

## Who is a CHAOSS repository maintainer?

The README.md of the repository contains a list of who is maintainer. Each CHAOSS repository brings together different people and they document in the repository specific CONTRIBUTING.md how somone becomes a maintainer on their repository.

