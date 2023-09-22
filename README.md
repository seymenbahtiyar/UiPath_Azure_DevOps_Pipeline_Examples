# UiPath Azure DevOps Pipeline Examples

## Pipeline is triggered by manually entering variables for the relevant project


### Usage

Before using this pipeline, make sure to set the necessary variables as environment variables or pipeline variables. The following variables need to be defined:

- `Git_Source`: The source of your Git repository (e.g., `MyProject/MyRepo`).

- `Git_Repository_Name`: The name of your Git repository (e.g., `MyRepo`).

- `Orchestrator_Folder_Name`: The name of the Orchestrator folder (e.g., `Shared`).

Adjust the UiPathPack and UiPathDeploy task configurations as needed for your project.

## When committed, the pipeline is triggered for the relevant project


### Usage

Update the repository configurations in the resources section to point to your Git repositories.

Modify the triggers to suit your needs.

Adjust the UiPathPack and UiPathDeploy task configurations as needed for your project.

## Other templates

https://github.com/UiPath-US-Services/uipath-azure-pipeline-templates

