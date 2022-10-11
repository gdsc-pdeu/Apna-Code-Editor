# APNA-CODE-EDITOR

## Table of Contents

## Introduction
The project **Apna-Code-Editor** aims to build a fully-functional code editor developed natively for Python programming <br>
using Python3 programming language. A code editor should have the following functionalities:
- Code writing capabilities
- Open previously configured code
- Syntax highlighting
- Autocompletion and hints
- Save newly developed code
- Execute saved codes and show corresponding output.

Project Apna-Code-Editor is a native python3-built software that tries to achieve the above mentioned functionalities of <br>
an ideal text-editor.

## Features
As of now, the project has following functionalities:
- Open saved files
- Save new files
- Save changes to already changed files
- Run python programs
- Cut, Copy, Paste functionalities
- Toggle between Light and Dark theme

## Get Started
Step 1: Open a terminal/git bash <br>
Step 2: Run the following command <br>
```bash
[user@desktop local/path] $ git clone https://github.com/Kunal-Kumar-Sahoo/Apna-Code-Editor.git
```

Step 3: If you are using any Linux-based distro or macOS, you would need to install Tkinter<br>
- Debian-based distros:
  ```bash
  [user@desktop local/path] $ sudo apt update
  [user@desktop local/path] $ sudo apt install python3-tk
  ```
- Arch-based distros:
  ```bash
  [user@desktop local/path] $ sudo pacman -Sy
  [user@desktop local/path] $ sudo pacman -S tk 
  ```   
- RHEL-based distros:
  ```bash
  [user@desktop local/path] $ sudo dnf update
  [user@desktop local/path] $ sudo dnf install python3-tkinter 
  ```  
- macOS:
  ```zsh
  user@desktop local/path % pip3 install tk
  ```  
  
Step 4: Now run the program <br>
  ```bash
  user@desktop local/path $ python3 src/main.py
  ```

## Author

[Kunal Kumar Sahoo](https://github.com/Kunal-Kumar-Sahoo)

## Contribution Guidelines

Are we missing any of your favorite features, which you think you can add to it❓ We invite you to contribute to this project and make it better.
To start contributing, follow the below guidelines:

**1.** Fork [this](https://github.com/gdsc-pdeu/Apna-Code-Editor.git) repository.

**2.** Clone your forked copy of the project.

```
git clone https://github.com/<your_user_name>/Apna-Code-Editor.git
```

**3.** Navigate to the project directory :file_folder: .

```
cd Apna-Code-Editor
```

**4.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/gdsc-pdeu/Apna-Code-Editor.git
```

**5.** Check the remotes for this repository.

```
git remote -v
```

**6.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream main
```

**7.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**8.** Perfom your desired changes to the code base.

**9.** Track your changes:heavy_check_mark: .

```
git add .
```

**10.** Commit your changes .

```
git commit -m "enter Necessary message"
```

**11.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**12.** To create a pull request, click on `compare and pull requests`.

**13.** Add appropriate title and description to your pull request explaining your changes and efforts done.

**14.** Click on `Create a Pull Request`.

**15** Voila!! You have made a PR to the Apna-Code-Editor . Wait for your submission to be accepted and your PR to be merged.



