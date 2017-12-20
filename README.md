# Andela DevOps Guide

## Introduction
This guide is a living document whose content aims to help novices, hobbyist and intermediate DevOps Engineers learn or up their skills in the DevOps space. The guide tackles are myriad of topics that take a learner right from the very basics on DevOps engineering to advanced techniques that can be used by Developers to own their projects into and during production.

## Technologies
- [Readthedocs](https://docs.readthedocs.io/en/latest/getting_started.html)
- [Sphinx](https://docs.readthedocs.io/en/latest/getting_started.html#in-rst)
- [reStrucutredText](https://www.youtube.com/watch?feature=player_embedded&v=oJsUvBQyHBs) OR [Markdown](https://docs.readthedocs.io/en/latest/getting_started.html#in-markdown)

## Contributing
Any one with knowledge to add to this guide is welcome to fork the repository anf update any area of interest i.e. networking, shell scripting. Make sure to add your content to a proper heading to make it easy for people reading the guide. These are some of the things to keep in mind as you do this;

#### Conributing to the main repository directly
- The master branch is protected and as such a contributor can not push updates/changes to it directly.
- Contributors will create branches in this format, `ch-update-to-networking`, in order to update the guide content. 
- When a contributor is satisfied with the update, they can raise a PR against the master branch.
- Once the updates have been reviewed and accepted by the administrators on the repository, the PR will be merged into the `master` branch.
- Once merged into master, these updates end-up on the web facing guide for all to see.

#### Contributing by creating a fork of the repository
- Fork this repository to your own github account.
- Make any changes you like to the `master` of your forked version.
- Raise a PR to the upstream `master` branch of the guide's repository so that your changes can be reviewed merged. This will automatically add them to the wed facing guide for all to see.

### Setup
- Clone the main project or fork you created.
- Ensure that you have `python` and `pip` installed.
- `cd` into the cloned folder.
- Run `pip install -r requirements.txt`.
- Follow the file structure to edit a subject of interest.