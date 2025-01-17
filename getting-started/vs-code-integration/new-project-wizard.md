---
title: Create New Project
page_title: Create New Project - Visual Studio Code Integration
description: Learn how to create a new Telerik UI for Blazor project with our Visual Studio Code Templates.
slug: getting-started-vs-code-integration-new-project
position: 2
---


# Create New Projects

This article demonstrates how to use the Telerik Extension for Visual Studio Code to create a new application that has the Progress&reg; Telerik&reg; UI for Blazor components working.

## Get the Extension

To use the **Telerik UI for Blazor Template Wizard**, install the Telerik UI for Blazor Visual Studio Code Extension. @[template](/_contentTemplates/common/general-info.md#vs-code-x-download)

## Start the Wizard

To create a Telerik-enabled Blazor project:

1. Press `Ctrl`+`Shift`+`P` in Windows/Linux or `Cmd`+`Shift`+`P` on Mac to open VSCode's extension launcher

    ![launch Telerik Blazor VS Code extension](images/launch-extension.png)

1. Type/Select `Telerik UI for Blazor Template Wizard: Launch` and press `Enter` to launch the extension

1. The wizard will now guide you through the project creation steps:
    1. choose a project name and location,
    
        ![choose Telerik project name and location](images/project-name-and-location.png)
        
    1. the type of project (WASM or Server-side) and your Telerik license (trial or commercial, depending on what you have),
    
        ![choose Blazor project type and Telerik license](images/project-type-and-license.png)
    
    1. add some sample pages to get you started (a grid with CRUD operations form a service, a form, charts),
    
        ![add sample pages](images/add-pages.png)
    
    1. choose a Theme.
    
        ![choose Telerik Theme](images/choose-theme.png)

1. When you open the project, to run it:

    1. Open the Terminal and navigate to the `Server` project folder. For a server project this is the folder with the project name, for a WASM project it will be the `Server` folder.

    1. Execute `dotnet run` and navigate your browser to the link you see in the console output.


>tip You now have a Blazor SPA app running!

