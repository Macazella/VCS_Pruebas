Branching & merging

cd checks/
git branch

Code output:

* master

git branch new-feature
git branch

* master

  New-feature

 
git checkout new-feature :

 How does git checkout switch branches? 
 By updating the working tree to match the selected branch.The HEAD is moved to the relevant commit on the specified branch.

Code output:

Switched to branch 'new-feature'


git checkout -b even-better-feature : Creates a new branch and switches to it.

Code output:

Switched to a new branch 'even-better-feature'


git branch -d new-feature 

Code output:

Deleted branch new-feature (was 80b2dac).


git merge even-better-feature 

Code output: 

Updating 7d1de19..4361880

Fast-forward

  free-memory.py | 6 ++++++

  1 file changed, 6 insertions (+)

  Create mode 100644 free_memory.py

git log

What happens when we merge two branches? Both branches are pointed at the same commit. Merging combines branched data and history together.




