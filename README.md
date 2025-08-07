# environment variables

C:\Users\Username\anaconda3

C:\Users\Username\anaconda3\Library\bin

C:\Users\Username\anaconda3\Scripts

# create environment

(bash)

    source activate base

    python --version

    conda create --name your_env_name python=your_python_version

    conda activate your_env_name

# delete environment

(bash)

    conda env list

    conda remove -n ENV_NAME --all

    conda env list

# others

(bash)

    conda list
    

# reference

https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

https://stackoverflow.com/questions/49127834/removing-conda-environment
