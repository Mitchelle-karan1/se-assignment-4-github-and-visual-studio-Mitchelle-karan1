[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15419724&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

GitHub is a web-based platform built around Git for version control and collaboration, widely used in software development. It offers a user-friendly interface to manage Git repositories and includes various features to facilitate collaborative work.


GitHub is a web-based platform built around Git for version control and collaboration, widely used in software development. It offers a user-friendly interface to manage Git repositories and includes various features to facilitate collaborative work.

Primary Functions and Features
Version Control:

Git Integration: Enables tracking of code changes, reverting to previous versions, and working on different branches simultaneously.
Commits: Record changes with messages describing updates.
Branches: Allow isolated work on features or fixes, which can be merged after review and testing.
Collaboration Tools:

Pull Requests: Propose, discuss, review, and test changes before merging.
Code Reviews: Team members review code, suggest improvements, and approve changes.
Issues and Bug Tracking: Track tasks, enhancements, and bugs, assign to team members, and link to pull requests.
Documentation:

README Files: Describe the project and provide setup and contribution instructions.
Wikis: Maintain detailed project documentation.
GitHub Pages: Host static websites for project documentation or personal sites.
Integration and Deployment:

GitHub Actions: Automate workflows, including continuous integration (CI) and continuous deployment (CD).
Webhooks and APIs: Integrate with other tools and services for notifications and deployments.
Community and Social Features:

Forking: Copy repositories to experiment with changes or start new projects.
Stars and Watch: Show appreciation and get updates on repositories.
Gists: Share code snippets or small scripts, publicly or privately.
How GitHub Supports Collaborative Software Development
Centralized Codebase: Provides a central repository accessible to all team members.
Streamlined Collaboration: Pull requests and branch management organize the collaboration process, enabling code reviews and discussions.
Transparent History and Accountability: Commit history and issues track changes and contributions, helping teams stay organized and on track.
Continuous Integration and Deployment: GitHub Actions automate testing and deployment, improving reliability.
Community Engagement: Facilitates open-source collaboration and onboarding of new contributors with comprehensive documentation.
Integration with Tools and Services: Integrates with development tools, project management software, and communication platforms for efficient collaboration.

Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.
A GitHub repository, often referred to as a "repo," is a storage space on GitHub where a project's files, history, and other essential components are kept. Repositories can be public (accessible to anyone) or private (restricted access). They support version control, collaboration, and documentation.

How to Create a New Repository
Sign In: Log in to your GitHub account.
New Repository: Click on the "+" icon in the upper right corner of the GitHub dashboard and select "New repository."
Repository Details: Fill in the required fields:
Repository Name: Choose a unique name for your repository.
Description (optional): Provide a brief description of your project.
Visibility: Choose between Public (anyone can see it) or Private (only you and selected collaborators can see it).
Initialize Repository (optional):
README: Add a README file to describe the project.
.gitignore: Choose a .gitignore template relevant to your project to exclude specific files or directories from being tracked.
License: Select a license to define how others can use your project.
Create Repository: Click the "Create repository" button.
Essential Elements of a Repository
README File:

Purpose: Provides an overview of the project, instructions on how to set it up, usage examples, and contribution guidelines.
Location: Typically located at the root of the repository.
Format: Written in Markdown (.md) format for easy readability.
LICENSE File:

Purpose: Specifies the terms under which the project's code can be used, modified, and distributed.
Location: Located at the root of the repository.
Common Licenses: MIT, Apache 2.0, GPL, etc.
.gitignore File:

Purpose: Lists files and directories that should be ignored by Git. This is useful for excluding temporary files, build outputs, and sensitive information.
Location: Located at the root of the repository.
Templates: GitHub offers templates for common programming languages and frameworks.
Source Code:

Structure: Organize the source code in a logical directory structure.
Conventions: Follow naming conventions and best practices relevant to the programming language used.
Documentation:

Purpose: Provides detailed information about the project, including how to use it, configure it, and contribute to it.
Formats: README file, Wikis, or dedicated documentation files/folders.
Issues and Pull Requests:

Issues: Used to track bugs, enhancements, and other tasks.
Pull Requests: Used to propose changes to the repository, facilitating code review and discussion before merging.
CI/CD Configuration (if applicable):

GitHub Actions: Automate workflows such as testing and deployment.
Configuration Files: .github/workflows directory for GitHub Actions workflows.

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?Concept of Version Control in the Context of Git
Version control is a system that tracks changes to files over time, allowing developers to record specific versions, or snapshots, of a project. This is crucial in software development as it enables multiple developers to collaborate on a project, revert to previous versions, and understand the history of changes. Git, created by Linus Torvalds, is one of the most widely used version control systems due to its distributed nature and powerful features.

Key Concepts of Git:
Repository (Repo): A repository is the directory where Git tracks and stores the project's files and history.
Commit: A commit is a snapshot of the project at a particular point in time. Each commit has a unique identifier (SHA) and includes a commit message describing the changes.
Branch: Branches allow developers to work on different features or fixes independently from the main codebase (often the main or master branch). Changes in branches can be merged back into the main branch once they're tested and approved.
Merge: Merging is the process of combining changes from different branches into a single branch.
Clone: Cloning a repository means creating a local copy of a remote repository on your computer.
Pull: Pulling updates your local repository with changes from a remote repository.
Push: Pushing sends your local changes to a remote repository.
Fetch: Fetching retrieves changes from a remote repository but does not merge them into your local branch.
Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches in GitHub are separate lines of development within a repository. They allow developers to work on different features, bug fixes, or experiments independently from the main codebase. The main branch, often named main or master, is considered the production-ready version of the code. Branches are crucial for enabling parallel development, code isolation, and collaborative workflows.

Importance of Branches
Isolation of Changes: Branches enable developers to work on new features or bug fixes in isolation, without affecting the main codebase.
Parallel Development: Multiple team members can work on different branches simultaneously, facilitating efficient parallel development.
Code Review and Testing: Branches provide a way to propose, review, and test changes before they are merged into the main branch.
Creating a Branch
Using GitHub Web Interface:

Navigate to your repository on GitHub.
Click on the "Branch" dropdown menu on the repository's main page.
Type a name for your new branch and press Enter.
Using Git Command Line:

Open your terminal or command prompt.
Navigate to your local repository.
Create a new branch with the command:

git checkout -b feature-branch
2. Making Changes
Using Your Local Development Environment:

Ensure you are on the new branch:

git checkout feature-branch
Make your changes to the code.
Stage the changes for commit:

git add .
Commit the changes with a descriptive message:

git commit -m "Implement new feature"
3. Pushing Changes to GitHub
Push your branch to the remote repository:

git push origin feature-branch
4. Creating a Pull Request
Go to your repository on GitHub.
Click the "Pull requests" tab.
Click the "New pull request" button.
Select your feature branch and compare it with the main branch.
Add a title and description for your pull request, then click "Create pull request."
5. Code Review and Approval
Team members review the pull request, leave comments, and suggest changes if necessary.
Once the changes are approved, the pull request can be merged.
6. Merging the Branch
Using GitHub Web Interface:

Go to the pull request page.
Click the "Merge pull request" button.
Confirm the merge by clicking "Confirm merge."
Using Git Command Line:

Switch to the main branch:
git checkout main
Merge the feature branch into the main branch:

git merge feature-branch
Push the updated main branch to the remote repository:
git push origin main
7. Deleting the Branch
Using GitHub Web Interface:

After merging, GitHub offers an option to delete the branch directly from the pull request page by clicking "Delete branch."

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
A pull request (PR) in GitHub is a feature that allows developers to propose changes to a repository. It facilitates the review and merging of changes from one branch into another, typically the main branch. Pull requests are essential for collaborative workflows, enabling multiple developers to contribute, review, and refine code before it becomes part of the main codebase.
How Pull Requests Facilitate Code Reviews and Collaboration
Code Review:

Discussion and Feedback: Pull requests provide a platform for team members to discuss proposed changes. Reviewers can leave comments, ask questions, and suggest improvements.
Approval Workflow: Changes can be approved by multiple reviewers, ensuring that the code meets the team's standards before it is merged.
Collaboration:

Centralized Communication: All discussions related to the proposed changes are centralized within the pull request, making it easy to track and refer back to them.
Visibility: Pull requests make the development process transparent, allowing team members to see what changes are being proposed and why.
Testing and Validation:

Automated Checks: Pull requests can be integrated with continuous integration (CI) tools to automatically run tests and checks on the proposed changes, ensuring they do not break existing functionality.
Version Control:

History and Documentation: Each pull request documents the changes made, including who made them, why they were made, and the discussion around them. This serves as a historical record and reference for future development.
Steps to Create and Review a Pull Request
Creating a Pull Request
Make Changes in a Branch:

Create a New Branch:
git checkout -b feature-branch
Make Your Changes: Edit files and save your changes.
Stage and Commit Your Changes:
git add .
git commit -m "Describe your changes"
Push the Branch to GitHub:
git push origin feature-branch
Create a Pull Request on GitHub:

Navigate to Your Repository on GitHub.
Click the "Pull Requests" Tab.
Click the "New Pull Request" Button.
Select the Branch: Choose the branch you want to merge (e.g., feature-branch) and the branch you want to merge into (e.g., main).
Review the Changes: Ensure the proposed changes are correct.
Add a Title and Description: Explain the changes and why they are needed.
Click "Create Pull Request".
Reviewing a Pull Request
Navigate to the Pull Request:

Go to the "Pull Requests" Tab in your repository.
Select the Pull Request you want to review.
Review the Changes:

Files Changed: Review the changes made in the pull request by clicking the "Files changed" tab.
Comments and Suggestions: Leave comments on specific lines of code or overall feedback using the inline comment feature.
Approve or Request Changes: You can either approve the changes if they meet the required standards or request changes if there are issues that need to be addressed.
Run Tests and Checks:

Ensure that automated tests and checks have passed. If any tests fail, review the issues and ask the contributor to address them.
Merge the Pull Request:

Once Approved and Tests Pass: Click the "Merge pull request" button and confirm the merge.
Optionally Delete the Branch: If the feature branch is no longer needed, delete it by clicking "Delete branch."
GitHub Actions:

 what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub ExplainActions.
 GitHub Actions is a feature within GitHub that allows developers to automate workflows for their repositories. It enables continuous integration (CI) and continuous deployment (CD), among other automation tasks, by using a configuration file to define the steps to be executed in response to specific events, such as pushing code to a repository or creating a pull request.

Key Features of GitHub Actions
Automation of Workflows: Automate tasks such as building, testing, and deploying code.
Event-Driven: Workflows can be triggered by events like commits, pull requests, issue creation, and more.
Customizable: Developers can define their own workflows using YAML syntax, specifying the steps and conditions for each task.
Reusable Actions: Actions can be reused across different workflows and repositories, promoting code reuse and consistency.
Integration with GitHub: Deep integration with GitHub makes it easy to use GitHub Actions with repositories, issues, pull requests, and more.
Example of a Simple CI/CD Pipeline Using GitHub Actions
Let's create a simple CI/CD pipeline that builds and tests a Node.js application every time code is pushed to the repository or a pull request is created.

Step 1: Create a Workflow File
Create a .github/workflows directory in the root of your repository if it doesn't exist.
Create a YAML file for your workflow, e.g., ci-cd-pipeline.yml.
Step 2: Define the Workflow
Here's an example of a simple CI/CD pipeline configuration:

name: CI/CD Pipeline

# Trigger the workflow on push or pull request events
on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    
    steps:
      # Checkout the code from the repository
      - name: Checkout code
        uses: actions/checkout@v2

      # Set up Node.js environment
      - name: Set up Node.js
        uses: actions/setup-node@v2
        with:
          node-version: '14'

      # Install dependencies
      - name: Install dependencies
        run: npm install

      # Run tests
      - name: Run tests
        run: npm test

  deploy:
    needs: build-and-test
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'  # Only deploy from the main branch

    steps:
      # Checkout the code from the repository
      - name: Checkout code
        uses: actions/checkout@v2

      # Deploy your application
      - name: Deploy
        run: |
          echo "Deploying application..."
          # Add your deployment script here
          # e.g., scp, rsync, or a deployment tool/command
Explanation of the Workflow
Trigger Events:

The workflow is triggered on push events to the main branch and on pull request events targeting the main branch.
Jobs:

build-and-test:

runs-on: Specifies the type of runner to execute the job (ubuntu-latest in this case).
steps: Defines the sequence of tasks to be executed:
Checkout code: Uses the actions/checkout@v2 action to clone the repository.
Set up Node.js: Uses the actions/setup-node@v2 action to set up a Node.js environment with version 14.
Install dependencies: Runs npm install to install the project dependencies.
Run tests: Runs npm test to execute the tests.
deploy:

needs: Specifies that this job depends on the successful completion of the build-and-test job.
if: Specifies a condition to run this job only on the main branch.
steps: Defines the sequence of tasks for deployment:
Checkout code: Uses the actions/checkout@v2 action to clone the repository.
Deploy: A placeholder step to add your deployment script (e.g., using scp, rsync, or a deployment tool).
Running the Workflow
Once you commit and push the .github/workflows/ci-cd-pipeline.yml file to your repository, GitHub Actions will automatically trigger the workflow based on the specified events (push or pull request). You can monitor the progress and results of the workflow runs in the "Actions" tab of your repository on GitHub.
Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Integrating GitHub with Visual Studio:
Visual Studio Code (VS Code) is a lightweight, open-source code editor also developed by Microsoft. It is designed to be fast, flexible, and customizable, catering to a wide range of development needs while being more lightweight compared to Visual Studio.

Key Features of Visual Studio Code
Code Editing:

Intellisense: Provides code suggestions, autocompletion, and error detection.
Syntax Highlighting: Supports a wide variety of languages with color-coded syntax.
Integrated Terminal:

Access to a terminal within the editor for running commands and scripts.
Source Control:

Built-in Git integration for version control and GitHub support.
Extensions:

Extensive library of extensions available in the Visual Studio Code Marketplace for adding languages, debuggers, tools, and services.
Customizability:

Highly customizable through settings, keybindings, themes, and extensions.
Debugger:

Integrated debugger for various languages and runtime environments.
Differences Between Visual Studio and Visual Studio Code
Purpose:

Visual Studio: A full-featured IDE designed for large-scale software development projects.
Visual Studio Code: A lightweight code editor designed for quick editing, flexibility, and extensibility.
Performance:

Visual Studio: More resource-intensive due to its comprehensive features.
Visual Studio Code: Lightweight and fast, suitable for quick editing and scripting tasks.
Language Support:

Visual Studio: Supports a wide range of languages natively, particularly strong in .NET and C++ development.
Visual Studio Code: Supports many languages through extensions, offering flexibility but requiring configuration.
Integrated Tools:

Visual Studio: Extensive integrated tools for project management, database interaction, and cloud services.
Visual Studio Code: Focuses on being a code editor with integrated Git support and relies heavily on extensions for additional functionality.
Customization:

Visual Studio: Customizable but more rigid due to its integrated nature.
Visual Studio Code: Highly customizable through settings and extensions, offering a more modular approach.
Integrating GitHub with Visual Studio
Setting Up GitHub in Visual Studio
Install Git:

Make sure Git is installed on your system. You can download it from git-scm.com.
Sign In to GitHub:

Open Visual Studio.
Go to File > Account Settings.
Sign in with your GitHub account.
Clone a Repository:

Go to File > Open > Open from Source Control.
Select GitHub and sign in if prompted.
Choose the repository you want to clone and select the local path where you want to clone it.
Create a Repository:

Open your project in Visual Studio.
Go to File > Add to Source Control.
Select Git to initialize a new Git repository.
Go to Team Explorer and click on the Sync option.
Click on Publish to GitHub.
Provide a name and description for your repository, then click Publish.
Using GitHub in Visual Studio
Commit Changes:

Open Team Explorer.
Go to the Changes section.
Stage your changes and provide a commit message.
Click Commit All or Commit Staged.
Push Changes:

In Team Explorer, go to the Sync section.
Click Push to push your committed changes to GitHub.
Create a Branch:

In Team Explorer, go to the Branches section.
Right-click on the current branch and select New Branch.
Provide a name for the branch and click Create Branch.
Create a Pull Request:

Push your branch to GitHub.
In Team Explorer, go to the Sync section.
Click Create Pull Request to open GitHub and create the pull request.

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?Steps to Integrate GitHub Repository with Visual Studio
Install Git and GitHub Extension for Visual Studio:

Ensure Git is installed on your system. You can download it from git-scm.com.
Install the GitHub Extension for Visual Studio:
Open Visual Studio.
Navigate to Extensions > Manage Extensions.
Search for "GitHub Extension for Visual Studio" and install it.
Sign In to GitHub in Visual Studio:

Open Visual Studio.
Go to File > Account Settings.
Sign in with your GitHub account. This step is necessary to authenticate your access to GitHub repositories.
Clone a GitHub Repository:

In Visual Studio, go to File > Open > Open from Source Control.
Select GitHub as the source control provider.
Sign in with your GitHub credentials if prompted.
Choose the repository you want to clone from the list of your GitHub repositories.
Select the local directory where you want to clone the repository.
Click Clone.
Working with Cloned Repository:

Once the repository is cloned, you can start working on your code within Visual Studio.
Visual Studio automatically detects Git repositories and provides integration in the Team Explorer pane.
Commit and Push Changes:

Make changes to your code in Visual Studio.
In the Team Explorer pane (View > Team Explorer), go to the Changes section.
Stage your changes by clicking on the + icon next to the files you want to commit.
Enter a commit message describing your changes.
Click Commit All to commit your changes locally.
To push your changes to GitHub, go to the Sync section in Team Explorer.
Click Push to push your committed changes to the remote repository on GitHub.
Create Branches and Pull Requests:

In Visual Studio, you can create new branches and switch between branches using the Branches section in the Team Explorer.
To create a new branch, right-click on the current branch and select New Branch.
Once you've made changes on a branch and want to merge them back into the main branch, you can create a pull request directly from Visual Studio.
Go to the Sync section in Team Explorer and click Create Pull Request to initiate the pull request creation process on GitHub.
How Does This Integration Enhance the Development Workflow?
Unified Environment:

Developers can work with Git version control and GitHub repositories directly within Visual Studio, without needing to switch between different tools or interfaces.
Efficient Collaboration:

Seamless integration with GitHub enables easy collaboration with team members. Developers can clone repositories, create branches, and create pull requests directly from Visual Studio.
Improved Productivity:

Visual Studio's integration with Git and GitHub streamlines common development tasks such as committing changes, pushing updates, and managing branches, reducing manual effort and errors.
Access to GitHub Features:

Developers can leverage GitHub's features like issue tracking, code reviews, and project management directly from Visual Studio, enhancing project visibility and organization.
Automated Workflows:

Integration with CI/CD pipelines and GitHub Actions allows developers to automate build, test, and deployment processes, ensuring code quality and consistency throughout the development lifecycle.

Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?Visual Studio provides powerful debugging tools that help developers identify and fix issues in their code efficiently. These tools are essential for troubleshooting errors, understanding program behavior, and ensuring the quality and reliability of software applications. Here’s an overview of the debugging tools available in Visual Studio and how developers can use them effectively:

Debugging Tools in Visual Studio
Breakpoints:

Functionality: Breakpoints pause program execution at specific lines of code, allowing developers to inspect variables, evaluate expressions, and analyze program state.
Types: Includes standard breakpoints, conditional breakpoints (trigger based on conditions), and tracepoints (log messages without pausing).
Watch Windows:

Functionality: Allows developers to monitor and evaluate variables, expressions, and objects during debugging.
Types: Local variables, global variables, objects, and expressions can be added to watch windows for real-time inspection.
Using Debugging Tools to Identify and Fix Issues
Setting Breakpoints:

Place breakpoints at critical points in your code where you suspect issues might occur (e.g., before a function call or within a loop).
When execution pauses at a breakpoint, use the Watch windows to inspect variables and evaluate expressions to verify program state.
Inspecting Variables:

Use the Locals and Autos windows to monitor changes in variable values during debugging sessions.
Watch windows allow for deeper inspection of specific variables or expressions, aiding in pinpointing where and why issues arise.
Stepping
Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
GitHub and Visual Studio together offer powerful capabilities for supporting collaborative development, combining robust version control, seamless integration, and efficient project management tools. Here’s how they can be used together and a real-world example of a project that benefits from this integration:

Using GitHub and Visual Studio for Collaborative Development
Version Control with Git:

GitHub serves as a central repository for storing and managing code changes using Git.
Visual Studio integrates Git directly into its IDE, allowing developers to clone repositories, commit changes, manage branches, and synchronize with GitHub seamlessly.
Collaboration Tools:

Pull Requests: Developers can create, review, and merge pull requests directly within Visual Studio, leveraging GitHub’s pull request workflow for code review and collaboration.
Issues and Projects: GitHub’s issue tracking and project management tools help teams organize tasks, track bugs, and plan project milestones, accessible and manageable from Visual Studio.
Integrated Development Environment (IDE):

Visual Studio provides a comprehensive IDE environment with advanced code editing, debugging, and testing tools, enhancing productivity and facilitating rapid iteration in collaborative environments.
Continuous Integration and Deployment (CI/CD):

GitHub Actions can be used to automate build, test, and deployment processes directly from repositories hosted on GitHub.
Visual Studio integrates with CI/CD pipelines configured using GitHub Actions, enabling automated workflows that ensure code quality and streamline deployment.
Real-World Example: "Project X"
Project X is a web application development project involving a team of developers working remotely. Here’s how GitHub and Visual Studio integration supports collaborative development in this scenario:

Repository Management: The project’s codebase is hosted on GitHub, allowing developers to clone the repository to their local machines using Visual Studio.

Branching and Pull Requests: Developers create feature branches directly from Visual Studio for new features or bug fixes. They use Visual Studio’s Git integration to commit changes locally, then push these branches to GitHub.

Code Review: Using GitHub’s pull request feature, team members review each other’s code changes, provide feedback, and suggest improvements directly in the pull request interface on GitHub.

Automated Testing and Deployment: CI/CD pipelines are set up using GitHub Actions. Upon pushing changes to the main branch or creating pull requests, automated tests (unit tests, integration tests) are executed. Deployment to staging or production environments is also automated based on predefined workflows.

Issue Tracking and Project Management: Project X uses GitHub Issues to track tasks, bugs, and enhancements. Team members can link issues to pull requests and monitor progress using GitHub Projects directly integrated into Visual Studio for visibility and collaboration.

Documentation and Wiki: The team maintains project documentation and user guides in the GitHub repository’s wiki pages. Visual Studio provides easy access to these documents, ensuring all team members have up-to-date information.

Benefits of Integration
Efficiency: Seamless integration between GitHub and Visual Studio streamlines workflows, reduces context switching, and enhances team productivity.

Collaboration: GitHub’s collaborative features combined with Visual Studio’s powerful IDE capabilities facilitate effective teamwork, code sharing, and knowledge transfer among team members.




Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
