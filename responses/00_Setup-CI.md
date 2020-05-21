# Welcome

Welcome to the Learning Lab course "Using GitHub Actions for CD". What is **CD**? If you don't already know, you'll find out soon! 

Before you get started, it's important that you are comfortable with a few skills. We recommend going through the [Introduction to GitHub Learning Lab course](https://lab.github.com/githubtraining/introduction-to-github/) and the [Hello, GitHub Actions! Learning Lab course](https://lab.github.com/github/hello-github-actions!) before beginning this one. 

Other experience with workflow automation will help, but are not necessary to complete this course.

### Set up CI Workflow

#### What is CI?

First, take a moment to examine the image below. It shows the relationship between **continuous integration**, **continuous delivery** and **continuous deployment**.

![](https://i.imgur.com/xZCkjmU.png)

**Continuous integration** (CI) is a practice where developers  integrate code into a shared branch several times per day.  The shared branch is sometimes referred to as **trunk**, but on Git, it's named **master**. To integrate code, developers **commit** on other Git branches, **push** their changes, and **merge** to master through **pull requests**. 

Automated events take place throughout this process. These events can range from running tests or deployments to cross-linking to relevant threads. Here's an example that we will use:

- Source code goes through an automated build process if necessary
- Automated testing of the software takes place
- Reports are generated and sent back to the developers with the status of their changes

**GOAL:** Regular code integration enables faster and easier error detection.

### Why do we need this?

**Continuous delivery** (CD) is the natural "next phase" of **continuous integration** (CI). Setting up a CI workflow will show us the entire picture of our workflow.

But, this is **NOT** a course on CI. We will not being going into detail on what CI means, or how to use CI with GitHub Actions.

Wait! There's good news 👍! If you need a CI refresher you can take the [Using GitHub Actions for CI Learning Lab course](https://lab.github.com/githubtraining/github-actions:-continuous-integration) to get up to speed.
