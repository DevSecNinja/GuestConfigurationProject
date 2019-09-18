# Guest Configuration Project

This module is a template
to use with the
[Plaster](https://github.com/powershell/plaster)
tool for scaffolding new projects.

## Demo

![gif](GuestConfigurationProject.gif)

## Setup

To use this solution on your dev workstation,
you will need to install the module from the
[PowerShell Gallery](https://powershellgallery.com).
This is easiest to do from PowerShell.

```powershell
Install-Module GuestConfigurationProject -repository PSGallery -force
```

This command will also install the following required modules if they
are not already available on the machine.

- Plaster
- Pester
- GuestConfiguration

This module include task runners for the
[VS Code](https://code.visualstudio.com/)
editor.
However, you could scaffold the project
and then open it in the editor of your choice.

## Contents

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `editor`          | Task runners for VSCode.                   |
| `Modules`         | Custom DSC resource modules.               |
| `test`            | Pester tests for custom resource modules.  |
| `.gitignore`      | Define what to ignore at commit time.      |
| `azure-pipelines.yml` | A build script for this project to automate publishing to PSGallery. |
| `CODE_OF_CONDUCT.md` | Code of conduct for participating in this community collaboration. |
| `Configuration.md` | A sample MOF file. |
| `GuestConfigurationProject.gif` | An animated demo.            |
| `GuestConfigurationProject.psd1` | Module manifest.            |
| `LICENSE`         | The license for the sample.                |
| `plasterManifest.xml` | Manifest file to define the Plaster template. |
| `project.code-workspace` | VS Code workspace settings.         |
| `README.md`       | This README file.                          |
| `SECURITY.md`     | How to report security issues.             |

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
