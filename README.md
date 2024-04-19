## TEADS-Generative-AI-Video-Classification

**Program**: Technology Excellence - Advanced Data Science (TEADS) Program - Generative AI Video Classification Project

**Authors**: Tim Tieng and Afia Owusu-Forfie

**Objective**: Develop a model to classify video content into categories such as sports, news, movies, etc., and enhance this classification by generating descriptive captions or summaries that provide additional context about the content. This can be particularly useful for content curation platforms, accessibility applications (e.g., providing descriptions for the hearing impaired), or educational tools where supplementary information enhances learning.


## Environment Setup

### System Requirements
- Ensure that `conda`, `pip`, and `pyenv` are installed on your machine globally.

1.  **Clone the Project Repository**

              git clone https://github.com/TimTieng/TEADS-Generative-AI-Video-Classification.git
              cd TEADS-Generative-AI-Video-Classification
       
2. **Virtual Environment Creation** - As a team, we confirmed to work on a stable version of Python, **3.10.12**. To accomplish this, we ran the following commands:

       # For pyenv-enabled machines
       pyenv install 3.10.12
       pyenv virtualenv 3.10.12 TechEx_Project3
       pyenv activate TechEx_Project3

       # For Conda Environments
       conda create -n TechEx_Project3 python=3.10.12
       conda init
       conda activate TechEx_Project3

4. **Package Installation** - To ensure  local machines have all the required packages, we created a "requirements" text files that was added to our "Config" folder. This text file has the package names required to complete this project. To install the packages outlined in the pip_requirements.txt file, we ran the following command in our local terminals within the to level directory of the project folder folder:

       pip install -r pip_requirements.txt
       conda install --file conda_requirements.txt

### Version Control Practices

1. **Branches Naming Convention**: Naming convention practices for local branch creation will be <FirstNameLastName_Project3>. After cloning the repository, run this command in your cmd prompt/terminal to create and checkout your branch

       git checkout -b <FirstNameLastName_Project3> # Please fill in with your own information; please do not include the "< >" symbols

2. **Set Upsteam Branch**: After creating your branch using the steps above, you need to set the upstream branch to track the remote repository. Run the following command:

       git push -u origin <FirstNameLastName_Project3>
   *Remember to replace with the name of your newly-created branch*

3. **Commits and Pushing Changes to the Repository**: Commit your local changes early and often with succinct detailed messages. **REMEMBER TO CLEAR ALL OUTPUTS IN YOUR NOTEBOOK FILE BEFORE PROCEEDING WITH THE STEPS BELOW**

       git status
       git add <name of modified local file>
       git commit -m "Meaningful Message of your change"
       git push origin HEAD
   
5. **Pulling Changes to Local Branches**: To minimize merge conflicts and effectively handle version control of notebooks, Project members will be working on their own notebook files and their own branches. If updated utility scripts or data file are added to the main repository, each project member is expected to switch to the main branch, pull the changes, and then switch back to their local branch. This will help minimize merge conflicts while ensuring all project members regardless of github expperience can use it. If changes are merged into main, local branches must be updated. The commands are as follows:

       git checkout main # Swtiches to the main branch
       git status #  Command will be used to verify if your local branch is behind/ahead
       git pull # pulls the latest changes from main to your local computer
       git checkout <Your branch>
       git pull # this additional pull will sync changes to your branch
