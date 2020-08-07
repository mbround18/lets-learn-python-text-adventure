# Python based Text Adventure

## About

The purpose of this repository is to teach python to my significant other and best friend. I decided to open source the repository in case others found it useful or would like to  provide feedback on the journey. :) I no means am expert at python and so some of my teachings are methodology barrowings from other programming languages. The code I will be using will be relatively simple with no advanced uses like machine learning, frontend/backend development, etc. 

## Pre-expectations

- Basic understanding of visual studio code.
- Familarity with terminal. 

## Setup

### Python, Pip, Virtual Env, Visual Studio Code

#### Windows

> We use chocolatey to install the required programs. Chocolatey is a package manager for windows and this will simplify our installation. If you are wondering what the tool is and how to use it please click on the link in step 2 and explore. You can skip the chocolatey install if already have it installed.

1. Launch a cmd window in administrative mode

   1. Click start
   1. type `cmd`
   1. Right click `Command Prompt`
   1. Click `Launch as Administrator`

1. [Install Chocolatey](https://chocolatey.org/install)

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
   ```

1. Close the commad prompt window.
1. Relaunch the command prompt window in administraitive mode.
1. Install Visual Studio Code and Python

   ```powershell
   choco install -y vscode python git
   ```

1. Now close the command prompt window.
1. Open a command prompt window normally.
1. CD into your documents folder

   ```
   cd Documents
   ```

1. Make a development folder.

   ```powershell
   mkdir develop
   ```

1. CD into the development folder.

   ```powershell
   cd develop
   ```

1. Clone the repo

   ```powershell
   git clone repo
   ```

#### Mac

> We will be using homebrew as its been the standard for installing development setups for quite some time on mac. If you have troubles, you can find an amazing userbase to ask questions online. 

1. Open a terminal window by hitting the command key + space bar and typing terminal.
1. [Install Homebrew](https://brew.sh)

   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   ```

1. Install python & git with homebrew

   ```sh
   brew install python git
   ```

1. [Install Visual Studio Code](https://code.visualstudio.com/docs/setup/mac)
1. cd into your home directory

   ```sh
   cd ~
   ```

1. Make a new directory for development.

   ```sh
   mkdir -p develop
   ```

1. CD into the development folder.

   ```sh
   cd develop
   ```

1. Clone the repo

   ```sh
   git clone repo
   ```

#### Linux (Preferred)

> Instructions will be for Ubuntu as a base since I am using and recommend Pop!\_OS from System76.

1. Open a new terminal window.
1. Install python and git
   ```sh
   sudo apt install git python
   ```
1. [Install Visual Studio Code (Prefferably not with snap)](https://code.visualstudio.com/docs/setup/linux)
1. cd into your home directory

   ```sh
   cd ~
   ```

1. Make a new directory for development.

   ```sh
   mkdir -p develop
   ```

1. CD into the development folder.

   ```sh
   cd develop
   ```

1. Clone the repo

   ```sh
   git clone repo
   ```

## Objective

Lets create a text adventure together that tells a simple story with a couple of different outcomes. In the lessions following this I will be telling the simple story of `The quick brown fox who jumps over the lazy dog`. A simple writing tool used by english and typing teachers to showcase each letter in the english alphabet.


## Lession Structure

### Structure

> The lession structure will be as follows in each subsequent outlined section. You are more than welcome to jump around between sessions as you go. 


#### Introduction

Every Session will have one of these and it will describe what we will be going over. 

#### Problem

This is the problem statement in which we are trying to solve. 

#### Pre-requisits

Any prior session that could be useful or knowlegde you are expected to have. 

#### Solution

The solution will always be in a seperate file. The solution provided will be one of many potential solutions because as with all programming, you have many ways you can solve a problem. You are always welcome to skip to the solution if you get stuck but please try to solve the problem before looking at the solution. 

## Lessions

- [01 - Story Boarding](lessions/01-story-boarding/readme.md)

