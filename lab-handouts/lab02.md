# Leverging Multiple Suggestions with GitHub Copilot

## Introduction

While GitHub Copilot offers suggestions for numerous languages and a variety of frameworks, it excels when it comes to Python, JavaScript, TypeScript, Ruby, Go, C#, and C++. The Copilot can also assist in query generation for databases.

In this exercise, you will have the opportunity to explore and apply the use of Python in conjunction with Copilot, and you will do so with the benefit of receiving multiple suggestions.

### Task 1

1. Install the Python extension in VS Code
 - Click on the **Extensions** icon in the activity bar present on the left side of the Visual Studio Code window
 - Search for the **Python** extension in the _Search Extensions in Marketplace_ search box
 - Select **Python** from the list of results that show up and **Install**

2. Create a **New File** named `app.py` in the `lab-files` directory and create a new function definition in the file:

```
def hello():
```

3. GitHub Copilot will automatically suggest code in gray text. Press Tab to accept the suggestion and then save the file. A suggestion will look similar to the following: 

```
def hello():
    return 'Hello, World!'
```

### Task 2

1. In the same file, type the following code: 

```
def prime(n):
```

2. Open a new tab with _multiple_ solutions by pressing `Ctrl + Enter`. GitHub Copilot will generate around 10 different code suggestions in a new tab. Here, you can view the solutions, accept a suggestion (by clicking on **Accept Solution**)

***Note:** Some suggestions provided by GitHub Copilot will be more accurate to your use case than others, please review code carefully to ensure that you are accepting code that will work correctly for your development needs.

3. Save the file.

### Task 3

1. Push your code to the repository using either method provided below

    #### Using Git Flow

    1. At the top of your VS Code window select the **Terminal** tab and click **New Terminal**. This will open a terminal window directly in your VS Code.
    2. Run the command below to add the `app.py` files to the GitHub repo

    ```
    git add app.py
    ```

    3. Commit the changes to the repo

    ```
    git commit -m "My Python copilot commit."
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

