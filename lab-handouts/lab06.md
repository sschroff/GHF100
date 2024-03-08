# Generating Documentation With Inline GitHub Copilot

## Introduction

GitHub Copilot can help streamline the process of generating documentation for your software projects. It assists by auto-generating code comments, creating Markdown documentation, providing templates for common sections, ensuring grammar and style consistency, and cross-referencing code and documentation. This tool can save time and improve the quality of your project's documentation, making it more accessible and user-friendly.

### Task 1

1. Create a new file named `document.md` and press `Ctrl + I` to open inline GitHub Copilot Chat
2. Type `Create a markdown document to create a virtual network Azure Portal` in the text area and click on `>` or press `Enter`
3. Copilot will give a response, review it, and click **Accept**. Save the file

### Task 2

1. Create a new file named `calculator_documentation.md` and press `Ctrl + I` to open inline GitHub copilot Chat
2. Type `Create markdown documentation for the code calculator.js. Including how it works and how to run the program` in the text area and click on `>` or press `Enter`
3. Copilot will give a response, review it, and click **Accept**. Save the file

### Task 3

1. Push your code to the repository using either method provided below:

    #### Using Git Flow

    1. At the top of your VS Code window select the **Terminal** tab and click **New Terminal**. This will open a terminal window directly in your VS Code.
    2. Run the command below to add the `document.md` and `calculator_documentation.md` files to the GitHub repo

    ```
    git add document.md calculator_documentation.md
    ```

    3. Commit the changes to the repo

    ```
    git commit -m "My copilot documentation commit."
    ```

    4. Push the code to the repo

    ```
    git push
    ```

    5. Wait approx. 1 minute and refresh your GitHub repository to ensure that the changes are reflected in your repository

    #### Using the VS Code Interface

    1. Click the VS Code **Source Control** tab on the left hand of your VS Code screen or press `Ctrl + Shift + G` 
    2. Stage your changes by clicking the small plus icon in the righthand corner of the panel
    3. Enter a commit message and select the **Commit** button
    4. Once changes are staged, click the elipses in the far right corner, choose **Push** and enter your password
    5. Wait approx. 1 minute and refresh your GitHub repository to ensure that the changes are reflected in your repository