---
title: "Git Going: A Step-by-Step Guide to Installing and Configuring Git"
seoTitle: "Install and Configure Git: Step-by-Step Guide"
seoDescription: "Step-by-step guide to understanding, installing, and configuring Git on Windows and Linux, plus basic Git commands to manage projects efficiently"
datePublished: Sun Sep 01 2024 11:36:42 GMT+0000 (Coordinated Universal Time)
cuid: cm0jhxvzy00080ammh98phtyo
slug: git-going-installation-guide
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1725194086587/95ade591-f9f9-4c2f-85c2-44c276428a91.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1725194529072/bbae3a7d-a8ea-45cb-a5ca-9bc91b851bd7.png
tags: newbie, linux, github, bash, git, windows, beginners, gitlab, installation, linux-for-beginners, gitcommands, linustorvald

---

In this blog, we'll explore the fundamentals of Git, understanding what it is and why it's an essential tool. We'll also guide you through the process of installing and configuring Git on both Windows and Linux platforms, ensuring you're well-equipped to manage your projects effectively.

---

# What is Git ?

Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It allows multiple people to work on a project simultaneously without interfering with each other's changes. By tracking and recording every modification made to a project's files, Git enables users to easily collaborate, revert to previous versions, branch off to develop new features, and merge changes back into the main codebase.Git's powerful branching and merging features, along with its strong support from platforms like GitHub, GitLab, and Bitbucket, have made it the most popular version control system in the world.

# Why use Git ?

**Benefits of Git in Version Control:**

* **Collaboration:** Git allows multiple developers to work on the same project simultaneously without overwriting each other's changes.
    
* **Version Tracking:** Every change is tracked, allowing you to revert to previous versions if needed.
    
* **Branching and Merging:** Git’s branching model lets you create separate branches for new features, bug fixes, or experiments, which can later be merged back into the main project.
    
* **Distributed System:** Each developer has a complete copy of the project history, making Git resilient to data loss and enabling work offline.
    

---

# Setting Up Git on Windows

### Step 1: Download Git

1. Go to the official Git website: [https://git-scm.com/](https://git-scm.com/).
    
2. Choose the Windows version and download the installer.
    

### Step 2: Install Git

1. Run the downloaded installer.
    
2. Guide through the installation process:
    
    * Default settings for most users.
        
    * On the 'Select Components' page make sure to check
        
        ✔️ **Add a git bash profile to Windows Terminal**
        
        This will significantly improve your experience.
        
    * Choosing the default editor (e.g., Vim, Notepad++).
        
    * On the 'Choose a Credential Helper' page  
        Choose **Git Credential Manager**  
        Again, this will be helpful later when we configure Git.
        
    * Configuring the initial branch name.
        

### Step 3: Verify Installation

* Open Command Prompt / Windows Terminal or Git Bash.
    
* Run `git --version` to confirm Git is installed correctly.
    

### Step 4: Configure Git

* Set your username: `git config --global` [`user.name`](http://user.name) `"Your Name"`.
    
* Set your email: `git config --global` [`user.email`](http://user.email) `"`[`your.email@example.com`](mailto:your.email@example.com)`"`.
    
* Verify configuration: `git config --list`.
    

---

# Setting Up Git on Linux

### **Step 1: Install Git**

* **For Ubuntu/Debian-based distributions:**
    
    * Open Terminal.
        
    * Run `sudo apt-get update`.
        
    * Install Git: `sudo apt-get install git`.
        
* **For Fedora-based distributions:**
    
    * Open Terminal.
        
    * Run `sudo dnf install git`.
        
* **For Arch-based distributions:**
    
    * Open Terminal.
        
    * Run `sudo pacman -S git`.
        

### **Step 2: Verify Installation**

* Run `git --version` in Terminal to ensure Git is installed correctly.
    

### **Step 3: Configure Git**

* Set your username: `git config --global` [`user.name`](http://user.name) `"Your Name"`.
    
* Set your email: `git config --global` [`user.email`](http://user.email) `"`[`your.email@example.com`](mailto:your.email@example.com)`"`.
    
* Verify configuration: `git config --list`.
    

---

# Basic Git Commands to Get Started

1. **Initialize a Repository**
    
    * `git init` – Start a new Git repository.
        
2. **Cloning a Repository**
    
    * `git clone <repository-url>` – Clone an existing repository.
        
3. **Checking Repository Status**
    
    * `git status` – Check the current state of the repository.
        

**Staging and Committing Changes**

* `git add <file>` – Stage changes.
    
* `git commit -m "commit message"` – Commit changes with a message.
    

---

# Conclusion

### **Recap of Git Setup**

In this blog, we covered the essentials of Git, including its purpose and benefits for version control. We provided step-by-step guides for installing and configuring Git on Windows and Linux platforms, and introduced basic commands to help you get started with managing your projects efficiently.

You can explore more and dive deeper into the world of Git by reffering to the [Pro Git book](https://git-scm.com/book/en/v2).

### Additional Resources

**Useful Links**

* Official Git Documentation: [https://git-scm.com/doc](https://git-scm.com/doc).
    
* GitHub Learning Lab: [https://lab.github.com/](https://lab.github.com/).
    

---

You can reach out to me via [Twitter](https://x.com/PiyushKrRai) or [Linkedin](http://www.linkedin.com/in/piyushkrrai)