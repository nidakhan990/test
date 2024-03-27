# GITHUB <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="8%" height="8%">   


| Author | Created on | Version | Last updated by | Last edited on |
| :------: | :----------: | :-------: | :---------------: | :--------------: |
| Nida Khan    | 19-03-24   | version 1.4 | Nida Khan         | 22-03-24       |



| Table of content|
| --------------- |
| 1. [Introduction](#introduction)
| 2. [Purpose](#purpose)
| 3.[ Key feature & functionalities](#key-feature--functionality)
| 4. [Pre-requisites](#pre-requisites)
| 5. [Software overview](#software-overview)
| 6. [System requirement](#system-requirement)
| 7. [Important ports](#important-ports)
| 8. [Contact info](#contact-information)
| 9.  [Reference](#reference)

## Introduction 

GitHub is as a platform for hosting code, facilitating version control and collaborative efforts. It enables seamless project collaboration regardless of location. This guide instructs you in fundamental GitHub concepts such as repositories, branches, commits, and pull requests, offering a comprehensive understanding of these essential elements.

Programmers can pick source codes in many different languages and use Git, the command-line interface, to make and keep track of any changes. As a result, every team member receives help to work together on multiple projects from any location, thanks to top-notch collaboration. As a token of its flexibility, GitHub lets users review previous projects created at an earlier point in time.


## Purpose
GitHub serves several purposes, acting as a platform for collaboration, version control, and software development. Here are some of the key purposes of GitHub:

| Purpose                         | Description                                                                                                                                                                                                                                                           |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version Control**            | - GitHub provides a system to track changes to code called Git. <br> - Developers can collaborate, manage versions, and work effectively on projects.                                                                                                                |
| **Collaboration**              | - GitHub offers tools for code review, issue tracking, and project management. <br> - Multiple developers can work on the same project simultaneously, sharing changes and resolving issues.                                                                      |
| **Code Hosting**               | - Millions of open-source projects are hosted on GitHub. <br> - Developers can publish their projects publicly or privately, making them accessible to collaborators and users.                                                                                      |
| **Community Engagement**       | - GitHub fosters a vibrant developer community. <br> - Developers can connect, share knowledge, participate in discussions, and contribute to open-source projects.                                                                                             |
| **Documentation**              | - GitHub provides features for creating comprehensive project documentation, including wikis and README files. <br> - Users and contributors can easily understand and contribute to projects.                                                                    |
| **Continuous Integration and Deployment (CI/CD)** | - GitHub integrates with CI/CD tools like GitHub Actions. <br> - Developers can automate build, test, and deployment processes, ensuring code quality and accelerating software updates.                                                             |
| **Project Management**         | - GitHub offers project management tools such as project boards, milestones, and issue trackers. <br> - Teams can organize, prioritize, and track their work throughout the software development lifecycle.                                                  |                                                                                                                                                       |


## Key feature & functionality

### Basic Features:
| **Benefit**                  | **Description**                                                                                                                                                              |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Smooth project management    | GitHub project management features are vast. It provides a place where project managers and developers can collaborate to coordinate, track, and update their work. With this, projects are fast, timely, and transparent. |
| Effective team management    | With GitHub, teams carry the same mindset, which makes them organized. Also, moderation tools, such as Issue and Pull Request Locking, help the team to focus on the code.                                                          |
| Safe packages                | Thanks to the GitHub introduction, you can publish packages privately, within the team, or publicly to the open-source community. You can then use or reuse the packages by downloading them from GitHub.                             |
| Improved code writing        | GitHub enables team members to review, develop, and propose new codes. They can also discuss any implementation and proposals before changing the source code.                                                                           |
| Easy code hosting            | Code hosting is another area that shows how functional GitHub is. You have all the code and documentation in one place. With the millions of repositories on GitHub, you have various tools to help you host and release code.  |


### Advanced Features:

1. **Unique code safety**:
GitHub is packed with dedicated tools to help individuals and teams identify and analyze vulnerabilities in the code that other tools tend to miss. Development teams everywhere can collaborate to secure the software supply chain from beginning to end.


- **Collabrations**: who can access your repositories
     ![Col4](https://github.com/nidakhan990/test2/assets/164150254/434b6617-4b51-4ba8-88cb-1188601bc49b)

- **Branch protection**: restricted branch for for the protection.
   
    
     ![r4](https://github.com/nidakhan990/test2/assets/164150254/aab94034-999e-4657-9087-30b6fbaa7e0c)
     ![R5](https://github.com/nidakhan990/test2/assets/164150254/b697898e-2184-46a2-803b-83907b8a01dc)


3. **GitHub Actions**: GitHub Actions is a versatile and powerful tool that allows developers to automate their workflows directly within GitHub repositories. It provides a wide range of functionalities, such as building, testing, and deploying code, making it an important part of any development process.

- You can improve your team's productivity and efficiency by creating custom workflows and automating repetitive tasks with GitHub Actions. It supports a variety of programming languages and platforms, allowing you to seamlessly integrate your tech stack.
- Create a new workflow file in your repository's ".github/workflows" directory to get started with GitHub Actions. In this file, you define the event that will initiate the workflow, the actions to be performed, and any necessary inputs and outputs.

Here are some workflow examples that show the power and versatility of GitHub Actions:

  | Workflow Name             | Description                                                                                                                                                                   |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Build and Test Workflow   | When a new pull request is created, this workflow is triggered. It validates the code, installs dependencies, builds the code, runs unit tests, and generates a test report. |
| Deployment Workflow       | When a new release is published, this workflow is triggered. It validates the code, builds it, packages it into a Docker container, and deploys it to a cloud platform like AWS or Google Cloud. |
| Notification Workflow     | When a new issue is created, this workflow is triggered. It notifies the relevant team members of the new issue by sending a notification to a Slack channel or an email address. |

  ![l6](https://github.com/opstree/spring3hibernate/assets/164150254/041feed4-b8a5-4869-8ea4-00c780ed83c8)

  
These workflows are just a few examples of what GitHub Actions can do. You can create workflows that are tailored to your specific project and team needs thanks to its flexibility and customization options.
-----------------------------------------
3. **GitHub Copilot**:
 - GitHub Copilot is an AI tool developed by GitHub and OpenAI to revolutionize code writing.
 - It uses machine learning to offer code suggestions and auto-complete as developers type.
 - Enhances productivity by reducing time spent on boilerplate code, allowing focus on project essentials.
 - Analyzes code to predict and recommend relevant snippets based on developer intent.
 - Assists in learning new languages and libraries by providing examples and suggestions.
 - Raises privacy and security concerns due to code analysis, potentially exposing sensitive information.
 - Concerns exist regarding bias in suggestions, as machine learning models may inherit biases from training data.
----------------------------------
4. **GitHub Pages** :
 - GitHub Pages is a free web hosting service provided by GitHub.
 - It allows users to host static websites directly from their GitHub repositories.
 - To use GitHub Pages, users need to create a GitHub account and repository.
 - Enable GitHub Pages in repository settings by selecting a source (main branch or specific folder).
 - Websites can be built using HTML, CSS, JavaScript, or static site generators like Jekyll.
 - GitHub Pages offers simplicity and quick setup without needing separate hosting or domain.
 - However, it's limited to hosting static websites; dynamic content or server-side processing requires alternative hosting services.
 
  ![Screenshot from 2024-03-21 15-59-54](https://github.com/OT-MICROSERVICES/salary-api/assets/164150254/b97c4b77-eba0-43cc-8989-9a1600a19e1c)

----------------------------------------------
5. **GitHub CLI**:GitHub CLI is a command-line interface tool that allows developers to interact with GitHub directly from the terminal. It provides a powerful set of features that can assist developers in more efficiently managing their GitHub repositories and workflows.

- GitHub CLI allows developers to create and clone repositories, create pull requests and issues, and merge changes from the command line. This can save time and increase productivity by allowing developers to complete tasks without switching between the terminal and the GitHub web interface.
- One of the most important advantages of GitHub CLI is its ability to help automate common tasks. GitHub CLI allows developers to create aliases for common commands, allowing them to complete tasks more quickly and efficiently.

The following are some examples of how to use GitHub CLI:

Creating a new repository:
<tab><tab><pre><code>gh repo create my-new-repo/repo</code></pre>

Cloning a repository:
##  
<tab><tab><pre><code>gh repo clone owner/repo</code></pre>

These are just a few examples of what GitHub CLI can do. With its powerful set of features and ability to automate common tasks, GitHub CLI can be a valuable tool for developers who want to manage their GitHub workflows more efficiently.

6. **GitHub Codespaces**:GitHub Codespaces is a new cloud-based development environment that enables developers to write, review, and collaborate on code directly from their browsers. Developers can use GitHub Codespaces to create a fully functional development environment that is hosted in the cloud and accessible from anywhere, at any time.

- With features like live sharing, real-time code editing, and integrated debugging, the platform is intended to  make it easier for developers to collaborate on projects. Codespaces also integrate with other popular tools such 
as Visual Studio Code, Git, and GitHub Actions, making it easier for developers to continue working with their existing workflows.
One of the primary benefits of using GitHub Codespaces is the ability to quickly create a new development environment with a few clicks. Developers can use pre-configured environments or create their own custom environments based on their specific requirements. This allows them to concentrate on writing code rather than configuring development environments.

- Developers can also collaborate on code in real-time using GitHub Codespaces. Developers can use the live sharing feature to invite others to join their Codespace and collaborate on code in real-time. This is especially useful when working on complex problems that require input from multiple developers.
** by pressing " ," after click on code option **

![Screenshot from 2024-03-21 16-28-39](https://github.com/OT-MICROSERVICES/documentation-template/assets/164150254/437f1ef7-9380-4891-8e96-250167fa7851)

7. **GitHub Wiki**:It is a collaborative space within a GitHub repository where users can create and maintain documentation, guides, notes, or any other content related to the project. It serves as a knowledge base for the project's contributors and users.

Key features of GitHub Wiki include:

| Feature              | Description                                                                                                                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Markdown Support     | GitHub Wiki supports Markdown, a lightweight markup language that allows users to format text, create headings, lists, links, images, and more using simple syntax.                                                                 |
| Version Control      | Just like the rest of the repository, the content in GitHub Wiki is version-controlled using Git. This means you can track changes over time, revert to previous versions, and collaborate with others using pull requests.          |
| Access Control       | You can control who can view and edit the Wiki by adjusting repository permissions. You can make the Wiki public, private, or restrict access to specific collaborators.                                                            |
| History and Revisions| GitHub Wiki keeps a history of changes, allowing users to view previous versions of pages, compare revisions, and see who made specific edits.                                                                                      |
| Search               | GitHub Wiki includes a search feature that helps users quickly find content within the Wiki.                                          
![w1](https://github.com/nidakhan990/test/assets/164150254/6bc85be1-bc0c-408a-bbfa-cedf01b80a00)
![w2](https://github.com/nidakhan990/test/assets/164150254/572b66da-6f5a-4c93-9643-478b625f8a28)

8. GitHub's free plan allows unlimited collaborators for public repositories, but for private repositories, it limits collaborators to three, including the owner. To have more collaborators for private repositories, users need to upgrade to paid plans like GitHub Pro, GitHub Team, or GitHub Enterprise Cloud.
    
## Getting Started
### Pre-requisites

| License Type | Description | Commercial use| Open Source|
| ---------- | ------- | --------- |------------|
| General Public License version 2.0   | Free and open for public use and modification. |  Yes|      Yes| 


## Software Overview

| Software | Version |
| --------------- | -------------- |
| github | 2.25.1 |


## System Requirement

| Requirement |	Minimum Recommendation |
| --------------- | -------------- |
| Processor/Instance Type |	One-Core/T2.micro instance |
|RAM|	1 Gigabyte |
|ROM(Disk Space)|	 8 Gigabyte or Higher|
|OS| Required	Linux(Ubuntu, CentOS, Red Hat Enterprise Linux (RHEL), and Debian)|


## Important Ports
| Ports|	Description|
| --------------- | -------------- |
|22	|Port 22 is used to establish an SSH connection to an EC2 instance and access a shell.
|443	|It is a standard port for secure communication over the internet between client and server.
| 80	|It is a standard port for  not secure communication over the internet between client and server.


## Contact Information
|Name	|Email address 📧|
| --------------- | -------------- |
|Nida khan|	[nida.khan.snaatak@mygurukulam.co](https://www.gmail.com/)|




## Reference
|Description	|Links|
| --------------- | -------------- |
|git hub action |https://docs.github.com/en/actions| 
| markdown reference points|https://www.knowledgehut.com/blog/web-development/what-is-markdown |
|Wiki|https://www.google.com/search?q=how+to+use+github+wiki&oq=how+to+use+github+wiki&gs_lcrp=EgZjaHJvbWUyCQgAEEUYORiABDIICAEQABgWGB4yDQgCEAAYhgMYgAQYigUyDQgDEAAYhgMYgAQYigUyDQgEEAAYhgMYgAQYigUyDQgFEAAYhgMYgAQYigUyBggGEEUYPNIBCDgwNzRqMGo0qAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:4a958318,vid:bnMl0d-RcPQ,st:0|













