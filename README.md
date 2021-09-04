create env

'''echo
conda create -n wq python=3.7 -y
'''

activate env
'''echo
conda activate wq 
'''

created a requirements.txt file 

install the requirements.txt

'''echo
pip install requirements.txt
'''


get the data

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commmit -m "first commit"

