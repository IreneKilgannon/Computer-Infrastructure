# Computer Infrastructure

![Banner](img/banner.png)

This repository contains the assessment tasks and project for the module, Computer Infrastructure as part of the [Higher Diploma in Science in Computing in Data Analytics](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics) at [Atlantic Technological University](www.atu.ie).

## Purpose of the Module

The purpose of the assessment, as described in the GitHub repository for [Computer Infrastructure](https://github.com/ianmcloughlin/2425_computer_infrastructure) is to demonstrate ability in the following:

1. Use, configure, and script in a command line interface environment.

2. Manipulate and move data and code using the command line.

3. Compare commonly available software infrastructures and architectures.

4. Select appropriate infrastructure for a given computational task.

## Outline of the Tasks and Project

The tasks and the project are fully outlined by the lecturer, Ian McLoughlin in the [README](https://github.com/ianmcloughlin/2425_computer_infrastructure/blob/main/README.md) for the Computer Infrastructure repository on GitHub. 

The assessment involves extensive use of the command line interface in GitHub Codespaces. 

The overall aim of the tasks is to create a bash script, weather.sh that downloads weather information from the Athenry weather station. All the necessary steps to achieve this, from the basics of creating directories and timestamped files to writing the bash script, are documented in ``weather.ipynb``. 

The project involves creating a GitHub Actions workflow using the bash script and automating it so that the weather data from the Athenry weather stations is downloaded at 10 am every day. 

The tasks and project are documented in ``weather.ipynb``, with separate headings for each part of the assignment. 

The final component of the assessment is an organized repository with a clear README and suitable gitignore. GitHub Issues was used to plan the work for each task. 

## Contents of this repository

The repository contains the following directories and files:

|Repository root |Subdirectory |Contents |
|---|--- |--- |
|data |weather |Downloaded weather data |
| |timestamps | txt files|
| | |formatted.txt |
|||20241022_124153.txt|
|img |-|.png files|
|.gitignore | | |
|README.md | | |
|weather.ipynb | | |
|weather.sh | |Bash script |
|requirements.txt | | |

## Installation

To run the file on your local system, the following must be downloaded and installed.

1. Download and install [Anaconda](https://www.anaconda.com/download). Anaconda is a Python distribution and comes with pre-installed packages. Please note that when installing Anaconda it is important to check the two boxes for:
  * Add Anaconda3 to my PATH environment variable.
  * Register Anaconda3 as my default.
  
![Anaconda](https://github.com/IreneKilgannon/pands-project/blob/main/images/Anaconda.png)

2. Download and install [Visual Studio Code](https://code.visualstudio.com/).

3. Download and install [git](https://git-scm.com/downloads).

4. Install [Cmder](https://cmder.app/)

5. Create a [GitHub account](https://github.com). 

6. Open Cmder (or the terminal of Visual Studio Code) and enter the following to clone the repository from GitHub onto your own machine:
  
    ``git clone https://github.com/IreneKilgannon/computer_infrastructure.git``

## Usage

As [GitHub Codespaces](https://github.com/features/codespaces) uses Visual Studio Code in a Linux environment, the command line (terminal) of Visual Studio Code is used to run the commands for the tasks and project. 

* In your GitHub account, create a GitHub repository. GitHub have a short guide on how to [create a new repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

There are a number of ways to create a new codespace in your GitHub account. 

* From the side bar, as shown in the image below. 

<img src="img/codespaces_a.png" alt="drawing" width="200"/>

Clicking on Codespaces, will bring you to a window that displays any codespaces that have been created. Clicking on the green 'New codespace' will create a new codespace in your repository. 

* Directly from the repository. Click on the green code button, followed by Codespaces tab. Clicking ``Create codespace on main`` will create a new codespace. Created codespaces can also be accessed from here too.

<img src="img/codespaces.png" alt="drawing" width="500"/>

When you are finished working in the codespaces, it is important to disconnect the codespace as it will continue running until it times out due to inactivity. Charges could be incurred unless it is disconnected. Closing the browser tab does not stop the codespace.

<img src="img/stop_codespace.png" alt="drawing" width="300"/>

Tip: If you are switching between the virtual machine on GitHub Codespaces to working on your local machine, in either the terminal of VSCode or Cmder perform a ``git pull`` in the computer_infrastructure directory. Also, after a new json file has been created by the GitHub Actions workflow, a ``git pull`` is required in GitHub codespaces to sync it with the repository.

[Quickstart for GitHub codespaces](https://docs.github.com/en/codespaces/getting-started/quickstart)

## Dependencies

Currently there are no special packages or libraries required. Any dependencies will be added to ``requirements.txt`` that is found in the root of the repository.

## Get Help

If you have any questions or queries you can contact me at g00220627@atu.ie or alternatively [submit an issue](https://github.com/IreneKilgannon/computer_infrastructure/issues).






