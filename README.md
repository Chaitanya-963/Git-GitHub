# Your First Cup of Git: The Chai Code Cohort Guide to Git & GitHub 👨🏼‍💻

<aside> 

**👉🏼 Introduction**
 

**Hey!** Welcome to Chai Code cohort team! As a company perspective Git and GitHub are very crucial technologies for version control, teamwork and collaboration.. So here is the “SOLUTION” this docs is meant to help you get started with them.

GitHub and Git will be your go-to tools for managing code changes, working together on features and settling disputes. Get ready to contribute successfully by following this onboarding guide

</aside>

Lets Go..!➡️

<aside>

👉🏼 The First question comes in mind will be.. What is **Git** and **GitHub**? 🤔

### Git

![img.icons8.png](img.icons8.png)

**Here is the answer** - Git is a distributed version control system that allows developers to track changes in their code, collaborate on projects, and manage versions efficiently. It helps ensure you can revert to earlier states of your project if necessary.

### GitHub

![img.icons8.png](831fed16-3794-44e9-a89a-cca05dbcea4a.png)

**Here is the answer** - GitHub is a cloud-based platform for hosting Git repositories(repos). It offers tools for team collaboration, including pull requests, issues tracking, and project records. GitHub is where Chai Code developer collaborate and maintain project repositories.

</aside>

<aside>


**👉🏻 Some additional info:**

- **Version control system?**
    
    The history of your code is managed via version control systems. They let you work together and keep track of file modifications. Software development requires version control systems. Think of version control as a game checkpoint. You can always return to the previous checkpoint and go to any point in the game. In software development, this idea is the same.
    
- **Repository?**
A **repository** (repo) is like a digital folder where your project's code, files, and version history are stored. It’s the core structure used by Git and GitHub to organize and manage projects.

</aside>

## 👉🏼 Installation of Git & GitHub:

1. **Installing Git**                                      
    - **Windows**
        - Download the git installer from [git-scm.com](https://git-scm.com/)
            
            ![image.png](image.png)
            
    - **MacOS**
        - Install homebrew if not already installed:
            
            ```
            /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
            ```
            
        - Install Git:
            
            ```
            brew install git
            ```
            
    - **Linux**
        - Use your package manager to install Git:
            
            ```
            sudo apt install git
            ```
            
    

1. **Configuring Git**
    - Using User name and email:
        
        ```
        git config --global user.name "Your Name"
        git config --global user.email "your.email@example.com"
        ```
        

1. **GitHub Account setup:**
    - Go to [GitHub](https://github.com/) and sign up for a free account.
        
        ![Screenshot 2025-01-06 200240.png](Screenshot_2025-01-06_200240.png)
        
    - Verify your email address.

## 👉🏼 Cloning the Chai Code Repository:

- So Now you create your GitHub account, now sign in.
    - Then go to repository section on GitHub.
    - Create new repo.
        - Dashboard view:
            
            ![Screenshot 2025-01-06 201933.png](Screenshot_2025-01-06_201933.png)
            
        - Repository section view:
            
            ![Screenshot 2025-01-06 202018.png](Screenshot_2025-01-06_202018.png)
            
    - Fill the details correctly:
        
        ![Screenshot 2025-01-06 202627.png](Screenshot_2025-01-06_202627.png)
        
    - Follow this quick setup in vs code terminal:
        
        ![Screenshot 2025-01-06 203228.png](Screenshot_2025-01-06_203228.png)
        
    - Then click on code button:
        
        ![Screenshot 2025-01-06 203338.png](Screenshot_2025-01-06_203338.png)
        
    - Copy the repository's HTTPS URL or SSH URL.
        
        ![Screenshot 2025-01-06 203528.png](Screenshot_2025-01-06_203528.png)
        
    - Clone the repository locally:
        
        ```
        git clone https://github.com/ChaiCode/example-repo.git
        cd example-repo
        ```
     