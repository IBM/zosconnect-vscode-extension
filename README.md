# IBM z/OS Connect development tools

IBM z/OS Connect development tools offers features for developing APIs and API requesters inside Visual Studio Code. Create projects for development and generate the language structures required for mainframe application development.

## Features

* Generate API provider and API requester projects
* Generate the copybooks and include files for the API provider or API requester without needing the full project structure.
* Code snippets for building API requester applications.

## Prerequisites

Review the [IBM z/OS Connect development tools License Agreement](http://github.com/IBM/zosconnect-vscode-extension/raw/main/product-licenses/LICENSE.txt) and [Third Party Notices](http://github.com/IBM/zosconnect-vscode-extension/raw/main/product-licenses/NOTICES.txt) before downloading.

## Requirements

The following extensions are bundled with IBM z/OS Connect Tools for Visual Studio Code during installation and are provided here for additional information.
* [Gradle for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-gradle)
* [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

## Commands

| Command | Description |
| --- | --- |
| Generate Copybooks | Generate the COBOL copybooks or PL/I includes for an API First or API Requester application |
| Create Project | Create a new API provider or API requester project |

## Extension Settings

This extension contributes the following settings:

* `zcon.providerVersion`: The version of the API provider Gradle plug-in to use.
* `zcon.requesterVersion`: The version of the API requester Gradle plug-in to use.
* `zcon.flattenOutput`: Specifies whether to remove the directory hierarchy from the generated copybooks.
* `zcon.pluginRepositories`: List of private maven repositories to use to download plug-ins and dependencies.
* `zcon.gradleArguments`: Arguments to be passed into the gradle process.

