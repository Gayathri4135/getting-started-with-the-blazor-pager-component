# Getting Started with the Blazor Pager Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Pager](https://www.syncfusion.com/blazor-components/blazor-pager) component application to page through ListView data. The Pager component is integrated with a ListView and updates the displayed records based on the currently selected page. This approach helps improve navigation and user experience when working with larger datasets by displaying only the records needed for the active page.

The sample showcases client-side paging logic and demonstrates how Pager events can be used to dynamically refresh displayed data in response to user interaction.

## Key Features

- Uses the `SfPager` component from the [Syncfusion.Blazor.Navigations](https://www.nuget.org/packages/Syncfusion.Blazor.Navigations) package.
- Uses the `SfListView<TValue>` component from the [Syncfusion.Blazor.Lists](https://www.nuget.org/packages/Syncfusion.Blazor.lists) package.
- Configures the Pager using the `PageSize` property to control the number of displayed records.
- Uses the `TotalItemsCount` property to define the total number of available records.
- Responds to pager navigation actions to update the displayed ListView records.
- Implements client-side paging logic by selecting records for the active page.
- Demonstrates integration between Pager and ListView components within a Blazor WebAssembly application.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

- `Client/Pages/Index.razor` — Main sample page demonstrating Pager and ListView integration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/pager/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.