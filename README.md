---
page_type: sample
languages:
- PowerShell
products:
- GuestConfiguration
description: "A community supported Plaster template to scaffold projects for custom Azure Policy Guest Configuration resources/configurations"
urlFragment: "https://github.com/microsoft/guestconfigurationproject"
---

# Guest Configuration Project

This module is a template
to use with the
[Plaster](https://github.com/powershell/plaster)
tool for scaffolding new projects.

## Demo

![GIF](GuestConfigurationProject.gif)

## Setup

To scaffold a new project,
save this module to a location on your
dev workstation.
Navigate to the template folder
and run the Invoke-Plaster command.

## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `editor`          | Task runners for VSCode.                   |
| `Modules`         | Custom DSC resource modules.               |
| `test`            | Pester tests for custom resource modules.  |
| `.gitignore`      | Define what to ignore at commit time.      |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |
| `plasterManifest.xml` | Manifest file to define the Plaster template. |

## Prerequisites

This project requires four PowerShell modules for the task runners to function.

- Pester
- GuestConfiguration
- Az.Accoutns
- Az.PolicyInsights

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
