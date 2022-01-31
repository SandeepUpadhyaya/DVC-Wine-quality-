Create env
'''bash
conda create -n wineqs python=3.7 -y
'''
activate env
'''bash
conda activate wineqs
'''
created a requiremnents.txt file
then installed those libraries
'''bash
pip install -r requiremnets.txt
'''
download the data from
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init
dvc init
dvc add data_given/winequality.csv

git add.
git commit -m "first commit"

onliner update for readme
'''bash
git add ..&& git commit -m "update Readme.md"
or
git add .


'''

adding repository
'''bash
git remote add origin https://github.com/SandeepUpadhyaya/DVC-Wine-quality-.git
'''

Pushing changes to the reposatory
'''bash

git push origin main
'''

git branch -M main

git push origin main

