# GitHub Actions Demo

This repository will serve as an example of how to use GitHub Actions for CI/CD purposes.

Feel free to edit this file in `feature` branches and watch how the Actions gets triggered.

## Instructions

First off, clone this repository by executing the following command:

```
git clone <repo-url>
```

Then, navigate to the `.github/workflows` directory and open the `learn-github-actions.yml` file.

There you will find a sample file with the following statements:

1. The name of the Workflow.
2. Which type of events and branches it will respond to.
3. The jobs to be executed.
4. The operating system it will be using 
5. The steps with their corresponding `action`/`command` to be executed on the virtual environment.

## Watch the Actions in action

In order to see the Actions running, follow these steps: 

1. In your local repository, make any changes to any of the files in this project and push those changes to `remote`/`origin`.
2. Navigate to the GitHub remote repository website.
3. Create a Pull Request for your branch and point it to `master`
4. Watch the Pull Request form or click on the the `Actions` tab.
