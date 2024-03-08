# Generating ARM and Terraform code with GitHub Copilot Chat

## Introduction

GitHub Copilot Chat allows you to ask coding questions and receive answers directly within the supported IDE. Copilot Chat can help you with a variety of coding-related tasks, like offering you code suggestions, providing natural language descriptions of a piece of code's functionality and purpose, generating unit tests for your code, and proposing fixes for bugs in your code.

**Use cases for GitHub Copilot Chat**

There are several situations in which GitHub Copilot Chat can help with coding.

- Generating unit test cases
- Explaining code
- Proposing code fixes
- Answering coding questions

### Task 1

1. In the VS Code activity bar, click the GitHub Copilot Chat icon to open the Chat Window

2. In the **Ask Copilot a question or type / for topics** text box, type the following command:

```
Write an ARM code for deploying a storage account to Azure with the code explanation.
```

3. After GitHub Copilot Chat processes your question, an answer will be provided (with code suggestions when appropriate) in the chat window

4. To insert code into a new file, Click on the **Ellipsis (...)** and select **Insert Into New File**

5. Save the file by `Ctrl + S` to save the file, name it `arm.json` and click on **OK**

### Task 2

1. Open the GitHub Copilot Chat Window by clicking the GitHub Copilot Chat icon

2. At the bottom of the Chat Window, type the following command:

```
Write a Terraform code for deploying a storage account to Azure with the code explanation.
```

3. After GitHub Copilot Chat processes your question, an answer will be provided (with code suggestions when appropriate) in the chat window

4. To insert code into a new file, Click on the **Ellipsis (...)** and select **Insert Into New File**

5. Save the file by `Ctrl + S` to save the file, name it `terraform.tf` and click on **OK**

### Task 3

1. Open the GitHub Copilot Chat Window by clicking the GitHub Copilot Chat icon

2. At the bottom of the Chat Window, type the following command:

```
Write a PowerShell script for deploying a storage account to Azure.
```

3. After GitHub Copilot Chat processes your question, an answer will be provided (with code suggestions when appropriate) in the chat window

4. To insert code into a new file, Click on the **Ellipsis (...)** and select **Insert Into New File**

5. Save the file by `Ctrl + S` to save the file, name it `powershell.ps1` and click on **OK**

### Task 4

1. Push your code to the repository using either method provided below

    #### Using Git Flow

    1. At the top of your VS Code window select the **Terminal** tab and click **New Terminal**. This will open a terminal window directly in your VS Code.
    2. Run the command below to add the `arm.json`, `terraform.tf` and `powershell.ps1` files to the GitHub repo

    ```
    git add arm.json terraform.tf powershell.ps1
    ```

    3. Commit the changes to the repo

    ```
    git commit -m "My copilot chat commit."
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
