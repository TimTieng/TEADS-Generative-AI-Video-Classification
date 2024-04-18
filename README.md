## TEADS-Generative-AI-Video-Classification

**Program**: Technology Excellence - Advanced Data Science (TEADS) Program - Generative AI Video Classification Project

**Authors**: Tim Tieng and Afia Owusu-Forfie

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
       conda create -n TechEx_Project3 python= 3.10.12
       conda activate TechEx_Project3

3. **Package Installation** - To ensure  local machines have all the required packages, we created a "requirements" text file that was added to our "Config" folder. This text file has the package names required to compelte this project. To install the packages outlined in the pip_requirements.txt file, we rand the following command in our local terminals within the "Config" folder:

       cd config
       pip install -r pip_requirements.txt
       conda install --file conda_requirements.txt

