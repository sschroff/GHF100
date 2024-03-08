# Creating Unit Test Functions with GitHub Copilot Chat

## Introduction

### Task 1

1. Create a new file named `calculator.js`

2. Navigate to GitHub Copilot Chat and give the following prompt:

```
Compose a full JavaScript program for constructing a calculator. This program should have multiple functions to perform the tasks of addition, subtraction, multiplication, division, taking user input, and providing output
```

3. Copy and paste the provided code into the `calculator.js` file that you just created

4. To generate tests for each function, select the function for which the test case must be generated. In the GitHub Copilot Chat window, type `/tests` and hit **Enter**

5. GitHub Copilot Chat will generate a test case for any function that is selection

6. Proceed to create tests for each of the functions adding them into a new file called `test.js`

### Task 2

1. Push your code to the repository using either method provided below:

    #### Using Git Flow

    1. At the top of your VS Code window select the **Terminal** tab and click **New Terminal**. This will open a terminal window directly in your VS Code.
    2. Run the command below to add the `calculator.js` and `test.js` files to the GitHub repo

    ```
    git add calculator.js test.js
    ```

    3. Commit the changes to the repo

    ```
    git commit -m "My testing copilot commit."
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