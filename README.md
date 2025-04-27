# DynamicPythonDotNet

![image](https://github.com/user-attachments/assets/ff17cf8c-86d9-4b22-901b-808946d3057c)

**DynamicPythonDotNet** is a .NET MAUI application that provides an interactive environment for writing, executing, and visualizing Python code directly in the browser. The project leverages Pyodide, a Python runtime for the web, to execute Python scripts dynamically and display the results in a user-friendly interface.

## Features

- **Python Code Editor**  
  - Powered by the Monaco Editor, users can write Python scripts with syntax highlighting and a clean interface.  
  - Includes a sample Python script to get started.

- **Dynamic Python Execution**  
  - Executes Python code in the browser using Pyodide.  
  - Supports Pandas for data manipulation and ensures the Python function returns a Pandas DataFrame.

- **Error Handling**  
  - Displays user-friendly error messages if the Python code does not return a valid Pandas DataFrame or encounters other issues.

- **Data Visualization**  
  - Converts the returned Pandas DataFrame into JSON format and displays it in a responsive data grid using Radzen DataGrid.

- **Interactive Buttons**  
  - **Get Code**: Retrieves the current code from the editor.  
  - **Update Code**: Updates the editor with a predefined sample script.  
  - **Execute**: Runs the Python code and displays the results or errors.

## Technologies Used

- **.NET MAUI**: Cross-platform framework for building native applications.  
- **Blazor**: Enables the use of C# for building interactive web UI components.  
- **Pyodide**: Executes Python code in the browser.  
- **Monaco Editor**: Provides a rich code editing experience.  
- **Radzen Blazor Components**: Used for UI elements like buttons and data grids.  

## How It Works

1. **Write Python Code**  
   Use the Monaco Editor to write or modify Python scripts.  
2. **Execute Code**  
   Click the **Execute** button to run the Python script in the browser.  
3. **View Results**  
   - If the script returns a Pandas DataFrame, the data is displayed in a Radzen DataGrid.  
   - If an error occurs, a descriptive error message is shown.

## Requirements

- .NET 9 SDK  
- A modern web browser (for Pyodide compatibility)
