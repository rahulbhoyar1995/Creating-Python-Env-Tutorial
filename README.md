# Creating Python Environment Tutorial
### Author : Rahul Bhoyar

Comprehensive tutorial guiding users through creating isolated Python environments using virtualenv. Step-by-step instructions for managing dependencies and keeping projects organized. Ideal for beginners and experienced developers alike.

### Why we need to create Python environments while working on Python projects ?
Imagine you have different projects, and each project requires different versions of Python or specific packages. Without creating separate Python environments, all your projects would share the same Python installation and packages. This can lead to conflicts and confusion, especially when different projects need different versions of the same package.

Creating Python environments allows you to keep each project isolated, like having separate rooms for different tasks. Each environment has its own Python interpreter and package dependencies. This isolation ensures that changes made in one project don't affect the others, reducing conflicts and making it easier to manage dependencies. In simple words, Python environments help keep your projects organized, clean, and running smoothly.

In this tutorial, we will explore the process of creating Python environments in a straightforward manner. We'll delve into the importance of isolating Python environments for different projects, ensuring clarity and efficiency in our development practices.

### (A) For iOS System
#### Step 1: Install Python

Before we start creating Python environments, ensure that Python is installed on your iOS device. You can check if Python is installed by opening the Terminal app and typing:
```
python --version
```
If Python is not installed, you can download and install it from the App Store or use a package manager like Homebrew.

#### Step 2: Install Pip

Pip is a package manager for Python that allows you to install and manage Python packages. To install Pip, open Terminal and run:

```
python -m ensurepip --upgrade
```
#### Step 3: Install Virtualenv

Virtualenv is a tool used to create isolated Python environments. You can install Virtualenv using Pip by running:

```
pip install virtualenv
```
#### Step 4: Create a Python Environment

Once Virtualenv is installed, navigate to the directory where you want to create your Python environment in Terminal. Then, run the following command to create a new Python environment named myenv:

```
virtualenv myenv
```
Replace myenv with the desired name for your environment.

#### Step 5: Activate the Environment

To activate the environment, run:

```
source myenv/bin/activate
```
You should see the environment name (myenv) appear at the beginning of your command prompt, indicating that the environment is active.

#### Step 6: Install Packages

With the environment activated, you can now install Python packages using Pip. For example:

```
pip install package_name
```
Replace package_name with the name of the package you want to install.

#### Step 7: Deactivate the Environment

When you're done working in the environment, you can deactivate it by running:

```
deactivate
```
This will return you to your global Python environment.

### (A) For Windows System
#### Step 1: Install virtualenv

If you haven't installed virtualenv yet, you can do so by opening Command Prompt and running the following command:

```
pip install virtualenv
```
#### Step 2: Create a Python Environment

Navigate to the directory where you want to create your Python environment using Command Prompt. Then, run the following command to create a new Python environment named myenv:

```
virtualenv myenv
```
Replace myenv with the name you want to give to your environment.

#### Step 3: Activate the Environment

After creating the environment, you need to activate it. In Command Prompt, run the following command:

```
myenv\Scripts\activate
```
You should see the environment name (myenv) appear at the beginning of your command prompt, indicating that the environment is active.

#### Step 4: Install Packages

Once the environment is activated, you can install packages using pip, and they will be installed only in this environment, keeping your global Python installation clean. For example:

```
pip install package_name
```
Replace package_name with the name of the package you want to install.

#### Step 5: Deactivate the Environment

When you're done working in the environment, you can deactivate it by running:

```
deactivate
```
This will return you to your global Python environment.

Congratulations! You've successfully created a Python environment on your iOS/Windows device using Virtualenv. 
You can now use this environment to work on Python projects with isolated dependencies.
