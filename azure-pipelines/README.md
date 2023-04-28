# Azure Pipelines Templates for .NET MAUI Apps

Here you will find templates for use with [Azure Pipelines](https://azure.microsoft.com/products/devops/pipelines) to build, distribute, test, etc. your .NET MAUI apps.

The templates in this folder are designed to run by itself, but with some knowledge of Azure Pipelines you should be able to modify and/or combine them.

## Getting Started

Move any of the templates into your repo root with the filename `azure-pipelines.yml`.

Depending on the `trigger` defined in each workflow it will be triggered by a commit, a tag/PR, a manual trigger or possibly others.

Typically you use one pipeline definition with Azure Pipelines. Multiple YAML files are possible, find out more [here](https://stackoverflow.com/a/56809695/1506387).

Each workflow will:
* use variables to make it easier to customize a build for consumers. This can be found under the `variables` section
* have a couple of lines of general description at the top describing what it does and things that are good to know
* optionally have comments inline to clarify the structure
