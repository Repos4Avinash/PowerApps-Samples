---
languages:
- typescript
products:
- power-platform
- power-apps
page_type: sample
description: "Sample that shows how to create an increment component using Power Apps component framework."
---

# Power Apps component framework: Implementing increment component

This sample component shows how to bind data with Power Apps component framework and error handling.

## Before you can try the sample components

To try the sample components, you must first:

1. Install [Npm](https://www.npmjs.com/get-npm) (comes with Node.js) or [Node.js](https://nodejs.org/en/) (comes with npm). We recommend LTS (Long Term Support) version 12.16.1 LTS because it seems to be the most stable.

1. Install [.NET Framework 4.6.2 Developer Pack](https://dotnet.microsoft.com/download/dotnet-framework/net462). 

1. If you don’t already have Visual Studio 2017 or later, follow one of these options:
   - Option 1: Install [Visual Studio 2017](https://docs.microsoft.com/visualstudio/install/install-visual-studio?view=vs-2017) or later.
   - Option 2: Install [.NET Core 3.1 SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1) and then install [Visual Studio Code](https://code.visualstudio.com/Download).

1. Install [Microsoft Power Apps CLI](https://aka.ms/PowerAppsCLI).
1. [Download](https://github.com/microsoft/PowerApps-Samples/tree/master/component-framework) the sample components so that you have a local copy.

## What this sample does

The increment component renders as a textbox with an `Increment` button in the runtime. The text box shows the current value and the `Increment` button is clickable. Whenever you click on the button, the value within the textbox is increased by 1. You can change the increment value when you are configuring the component to the columns on the form.

The increment value can be changed to any number you wish. The updated value flows to the framework through the *notifyOutputChanged* method.

If the value in the text box is a valid integer, then it updates the value to the component framework. You can continuously click the `Increment` button and update it. If it’s an invalid integer, an error message pops out.

## How to run the sample

See [How to run the sample components](https://github.com/microsoft/PowerApps-Samples/blob/master/component-framework/README.md) for more information about how to build and import components into Microsoft Dataverse.

## See also

[Power Apps component framework overview](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/overview)<br/>
[Power Apps component framework API reference](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/reference/)<br/>
[Power Apps component framework manifest schema reference](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/manifest-schema-reference/)