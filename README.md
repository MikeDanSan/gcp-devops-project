# gcp-devops-project
This repository is for practice for using google cloud platform to set up CI/CD and some DevOps practice.

## DevOps best practices

### Branch protection

Enable branch protection on the main branch of the repository to prevent unreviewed branch merges from affecting the working state of main.
To do this in Github you can add branch protection to add requirements to be met before any merges take place. In my example I require a pull request to be reviewed and approved before merges.

Steps to add branch protection:
* settings
* Branches
* Add branch protection rule
* Require a pull request before merging
* Options of how strict the pull request is chosen.

## Adding code to repo so the project has an application

### Docker flask application

- This application is written in python
- It will be deployed on GKE
