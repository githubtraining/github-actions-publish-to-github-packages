# Course description

GitHub Actions makes it easier than ever to incorporate continuous delivery (CD) into your repositories.  This course will teach you what is needed to test and deliver artifacts that are ready for deployment.

# What you'll learn
After taking this course, you'll be able to:

- Describe CD and why it is necessary
- Use and customize a repository workflow
- Create CD workflows that matches the team's needs and behaviors
- Use the repository's source code to build artifacts and store them in the GitHub Packages
- Save repository build artifacts
- Access saved build artifacts

# What you'll build

![GIF of a pull request, clicking on a commit status, shows logs of a package publishing, then shows package on the GitHub repository](https://user-images.githubusercontent.com/16547949/74983056-51122480-5403-11ea-8c86-29c42e69fb87.gif)

- Completed [source repository](https://github.com/githubtraining/github-actions-for-packages-demo)
- GitHub Actions [workflow](https://github.com/githubtraining/github-actions-for-packages-demo/runs/458940996?check_suite_focus=true) for creating the Docker image, tagging, and pushing to GitHub Packages
- [Docker image](https://github.com/githubtraining/github-actions-for-packages-demo/packages/133342) pushed to GitHub Packages

# Prerequisites

We recommend you first complete the following courses:
- [Hello, GitHub Actions!](https://lab.github.com/github/hello-github-actions!)
- [GitHub Actions: Continuous Integration](https://lab.github.com/githubtraining/github-actions:-continuous-integration)

# Projects used
This makes use of the following open source projects. Consider exploring these repos and maybe even making contributions!

- [actions/checkout](https://github.com/actions/checkout): Action for checking out a repo
- [actions/upload-artifact](https://github.com/actions/upload-artifact): Upload artifacts from GitHub's built-in artifact storage.
- [actions/download-artifact](https://github.com/actions/download-artifact): Download artifacts from GitHub's built-in artifact storage.
- [actions/setup-node](https://github.com/actions/setup-node): Set up your GitHub Actions workflow with a specific version of node.js
- [mattdavis0351/actions/docker-gpr](https://github.com/mattdavis0351/actions/tree/master/docker-gpr): A GitHub Action to upload Docker images to the GitHub Package Registry.

# Audience