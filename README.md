## TEADS-Generative-AI-Video-Classification

**Program**: Tech Excellence Advanced Data Science Program - Generative AI Project

**Authors**: Tim Tieng and Afia Owusu-Forfie

## Environement Setup

1. Pyenv Installation - We confirmed as a group that we have the package 'pyenv', 'virtualenv' installed locally to our machines. This allows us to make setup virtual environments to manage this project. Prior to starting, ensure that you have *conda*, *pip*, and *pyenv* installed on globally on your machine.

2. Project Folder Creation - Additionally, we made sure that we have the same folder structure for project 2. We ensured that we have the following directories present/created on our local machines: Config, Data, Notebooks. This can be updated as the project progresses.

3. Virtual Environment Creation - As a team, we confirmed to work on a stable version of Python, **3.10.12**. To accomplish this, we ran the following commands:

       # For pyenv-enabled machines
       pyenv install 3.10.12
       pyenv virtualenv 3.10.12 TechEx_Project3
       pyenv activate TechEx_Project3

       # For Conda Environments
       conda create -n TechEx_Project3 python= 3.10.12
       conda activate TechEx_Project3

4. Package Installation - To ensure  local machines have all the required packages, we created a "requirements" text file that was added to our "Config" folder. This text file has the package names required to compelte this project. To install the packages outlined in the pip_requirements.txt file, we rand the following command in our local terminals within the "Config" folder:

       pip install -r pip_requirements.txt

