# Part3: Recipe Application

Part3 is a Windows Presentation Foundation (WPF) application designed for managing recipes. Users can enter new recipes, display a list of all recipes, and view detailed information about individual recipes. This application showcases how to build a functional and user-friendly WPF application using C#.

## Features

Part3 includes several key features:

1. **Recipe Entry**: Users can input new recipes, specifying ingredients and step-by-step instructions.
2. **Recipe Display**: The application provides a list of all entered recipes, enabling users to browse through their collection.
3. **Detailed View**: Users can select a recipe from the list to view its detailed information, including ingredients and preparation steps.
4. **Caloric Warning**: The application includes a notification system that warns users if the total calories of a recipe exceed 300, promoting health-conscious cooking.

## Prerequisites

Before you can compile and run Part3, ensure you have the following software installed:

- **Visual Studio 2019 or later**: This integrated development environment (IDE) provides the necessary tools for building WPF applications.
- **.NET 6.0 SDK or later**: The software development kit required for building and running .NET applications.

## Installation

### Cloning the Repository

Begin by cloning the Part3 repository from GitHub. Open a terminal or command prompt and execute the following commands:

```sh
git clone
cd Part3
```

### Opening the Project in Visual Studio

Launch Visual Studio and open the project:

1. Select `File > Open > Project/Solution`.
2. Navigate to the `Part3` directory.
3. Select the `Part3.sln` file to open the project.

## Building the Project

### Restoring NuGet Packages

NuGet packages required by the project should be restored automatically by Visual Studio. If this does not happen, manually restore them by right-clicking the solution in the Solution Explorer and selecting `Restore NuGet Packages`.

### Building the Solution

To build the project, select `Build > Build Solution` or press `Ctrl+Shift+B`. Ensure the build completes without errors before attempting to run the application.

## Running the Application

### Starting the Application

To run Part3, select `Debug > Start Debugging` or press `F5`. This will launch the application and open the main window.

### Using Part3

The application interface is straightforward and intuitive. Here’s how to use the key features:

1. **Enter a New Recipe**: Click on "Enter a new recipe" to open the recipe entry panel. Fill in the recipe name, ingredients, and steps. After entering the required information, click "Submit Recipe" to save the recipe.
   
2. **Display All Recipes**: Click on "Display all recipes" to view a list of all the recipes you have entered. The list is displayed in a ListView control.
   
3. **Display a Recipe**: Click on "Display a recipe," select a specific recipe from the list, and click "Show Recipe" to view its details, including ingredients and preparation steps.
   
4. **Exit**: Click on "Exit" to close the application.

## Code Structure

The Part3 project is structured to separate concerns and maintain clarity. Here’s an overview of the key files:

- **MainWindow.xaml**: This file contains the XAML layout for the main window. It defines the UI elements and their arrangement, including panels for entering recipes, displaying all recipes, and displaying a single recipe.

- **MainWindow.xaml.cs**: This C# file serves as the code-behind for `MainWindow.xaml`. It contains the logic for handling user interactions and managing the application's functionality. Event handlers for button clicks and other UI actions are defined here.





Part3 is a versatile and user-friendly WPF application that makes managing recipes simple and efficient. By following this guide, you can easily compile, run, and use the application, as well as contribute to its ongoing development. Whether you’re a seasoned developer or a beginner, Part3 provides a practical example of building a functional WPF application with C#.
