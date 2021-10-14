# Version Control Systems
This page covers why using a Version Control System (VCS) is beneficial to your organization. This is demonstrated by using Git. GitHub will be used as an online hosting service for managing Git repositories.
## What is a Version Control System (VCS)
A VCS is a centralized source for storing files that helps to categorize and record file changes. This is done by tracking all code modifications through "commits" (committed changes to your file) in a file repository (repo). A repo contains all of the changes and historical versions of a project. By centralizing your source code it's easier to collaborate with team members who may or may not be in different locations.
In using a VCS, your organization will be able to communicate and better manage all file changes - showing information on who made the file change and when it occured. Individuals can make file contributions in different "branches" that are separate from the main source code. This allows for a proper assessment to occur before major changes are applied to the file.
<br /> 
<br /> 
**Example of a file in the Main Branch of the project repository**
<br /> 
<br /> 
![MainBranch](https://user-images.githubusercontent.com/90650872/137340313-3490354b-015c-436c-97b9-e9c985ee5bff.png)
<br /> 
<br /> 
## The Benefits and Uses of a VCS:
* For Disaster Recovery or project changes you can recover old file versions.
* Different "branches" allows for contributors to work on different aspects of a project without affecting the main source.
* Avoids errors and file conflicts by only adding to main branch once file is properly validated.
* Easier to collaborate on projects with a centralized source for files.
* Tracks who and when file changes occurred

## How to Make Changes using Git
* Make file changes
* Add changes to Git repo `git add FILE`
* Commit changes to the file `git commit -m "MESSAGE ABOUT FILE CHANGE"`
* Select appropriate "branch" you are working from `git checkout -b "DEV_BRANCH"`
* Push the committed changes to your branch in the online project repo (ex GitHub) `git push origin "DEV_BRANCH"`
<br /> 

**Example of a file version history**
<br /> 


<br />

![VersionHistory](https://user-images.githubusercontent.com/90650872/137341752-74e917b7-ce49-45dc-a9d8-3dd7d9ac9775.png)

## Importing Caylent's Github resources to terraform state
Please refer to [Caylent's Github organization README](https://github.com/caylent/caylent_github/blob/master/README.md) 

## Managing Caylent's Github organization with Github Terraform Provider and Terraform Cloud (TC)
Please refer to [Caylent's Terraform Github module README](https://github.com/caylent/library/blob/0.12/Terraform/modules/github/README.md) 

## Authors

Caylent Inc.
