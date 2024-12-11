# Learning Resource Library

## Overview

Compiled by members of the [Michigan Alzheimer's Disease Center's (MADC)](https://alzheimers.med.umich.edu/aboutus/) Data Core, this site contains a growing list of resources for current and newly on-boarded staff to build technical skills supporting the MADC's day-to-day work.


## Access the Learning Resource Library

Bookmark the link for future reference: <https://mleighc.quarto.pub/madc-learning-resource-library/>

Or grab the shortlink to share: [bit.ly/madc-learn](https://bit.ly/madc-learn)


## Contribute to the Learning Resource Library

If you would like to make suggestions of resources to include or provide other feedback related to this library, [please submit this form](https://forms.office.com/r/Y5DYvLgYEJ). The team will review your suggestions and update the library regularly.

The full link shared in-text is: <https://forms.office.com/r/Y5DYvLgYEJ>


## CI/CD Deployment Workflow

This repository uses two CI/CD systems:

> #### GitLab CI/CD
> - **Real Deployment**: The actual deployment of the Quarto-based resource library happens through GitLab. The GitLab CI/CD pipeline publishes the site to Quarto Pub. 
> #### GitHub Actions
>- **Dry-Run Deployment**: GitHub Actions is used to simulate the deployment process. It demonstrates the steps in the GitLab CI/CD pipeline but does **not** perform the actual deployment to Quarto Pub.

Both workflows trigger on pushes to the `main` branch. You can find more details about each system in their respective configuration files:
- **GitLab CI/CD**: `.gitlab-ci.yml`
- **GitHub Actions**: `.github/workflows/ci.yml`

This setup allows me to showcase my deployment automation skills in GitHub while using GitLab for production deployments.
