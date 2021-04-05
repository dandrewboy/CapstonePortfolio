# CapstonePortfolio
## Abstract
  The main goal this project aims to achieve is to offer a solution to helping use and manage the Docker software. Docker normally runs off the command line, which to some users can be difficult to use if they’re not familiar with using the command line. It also becomes difficult to manage multiple containers at the same time. With this project a user can open a container for any project they might have and manage and organize multiple containers being able to create containers for additional projects and delete containers for project they have since finished working on. 
## High Level/Non-Functional Requirments
### High Level Requirments
- Setting up the GUI
  - Allows for the user to have an easy to understand interface for interacting with Docker
- Opening/Reading Files
  - Allows users to select a project file
  - Application reads the file and identifies languages and technologies used
- Communicate with Docker
  - Application sends docker commands on behalf of the user
  - This involves running, managing, and deleting containers and images
- Manage Containers
  - Displays a list of containers so users know whats currently running
  - Selecting a container gives the option for the user to delete a container
- PhP/Java/C# Support
  - Allows the user to make containers for PhP, Java, and C# applications
### Non-Functional Requirments
- Manage Images
  - Allows the user to manage multiple containers
  - Allows for the use of multiple IDE's and other technologies
- Prefrence Settings
  - Allows the user to use a prefered IDE for specific languages
  - Can also be used for prefered Database services
## Technologies
- Docker Desktop v3.2.2
> Note: This version of Docker was built to work for Windows, allowing for PowerShell to run docker.
> Should versions of this application be created for use on another OS Docker Desktop is not specifically
> required for the application to work.
- Visual Studio 2019 v16.8.4
- .NET Core v5.0
- .NET Framework v3.0
> Note: >NET Core & .NET Framework where used to support the specific C# framework I was using for the application.
> A version not using C# or the .NET framework would not need these to run the application
- VMware Workstation Player v16.1.1
> Note: I had to use VMware due to some technical difficulties during development and therfore not required to run the application
## Technical Approach

## Risks & Challenges
## Outstanding Issues
