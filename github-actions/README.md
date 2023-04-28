# GitHub Action Templates for .NET MAUI Apps

Here you will find templates for use with [GitHub Actions](https://github.com/features/actions) to build, distribute, test, etc. your .NET MAUI apps.

The templates in this folder are designed to run by itself, but with some knowledge of GitHub Actions you should be able to modify and/or combine them.

## Getting Started

Move any of the templates in this folder to a folder in your own repository. The folder should be named `.github/workflows`.

Depending on the `trigger` defined in each workflow it will be triggered by a commit, a tag/PR, a manual trigger or possibly others.

You can have multiple workflows in one repository as long as the filename of each workflow is unique.

Each workflow will:
* use variables to make it easier to customize a build for consumers. This can be found under the `env` section
* have a couple of lines of general description at the top describing what it does and things that are good to know
* optionally have comments inline to clarify the structure

## Contents

| Name      | Description   | Link     |
| ----------- | ----------- | -------- |
| Basic CI, all platforms | Builds the .NET MAUI project for all target platforms in release configuration | [basic-ci.yml](basic-ci.yml) |