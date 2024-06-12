# DVC-demo

- DVC is a tool for data science that takes advantage of existing software engineering toolset. It helps machine learning teams manage large datasets, make projects reproducible, and collaborate better.

- DVC can be installed on Visual Studio Code, any system terminal, and used as a Python library.

- Data Version Control tool
- Some time we put our data as well on GitHub like .csv file and all. But if data is small then its fine but if its huge then GitHub will not allow it then what to do? that’s where the role of DVC comes
- If data is huge then you will not be able to push the data to GitHub and that problem is solved DVC.
- Using DVC, without committing huge data to your git repo we can control its version.
- In Git we only tracking the metadata of huge files and actual data can be stored/tracked by some other system, could be in Git or AWS S3 or Azure
- DVC manages the Metadata version for us which in turn manages the actual data version on other systems.

        conda create -p venv python==3.10 -y
        conda activate ./venv
        pip install -r ./requirements.txt
        pip list
        dvc init
        dvc add data/test.csv
        python ./demo_01.py
        python ./demo_01.py
        git status
        dvc add data/data.csv
        git status
        git add .
        git status
        git commit -m "first commit dvc"
        git branch
        git remote -v
        git push -u origin main
        git log
        dvc add data/data.csv
        git status
        git add .
        git commit -m "2nd commit"
        git push -u origin main
        git log
        git checkout e8ac4
        dvc checkout
        git checkout 938e9
        dvc checkout
