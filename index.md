# Lab Report 4
## Step 4:
<img width="719" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/ac180931-13b9-4d15-b6d8-6c63c370eb82">
<img width="698" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/0a5e6586-630c-42cd-acfb-fd7f22bc6a75">

Keys pressed: Type ```ssh cs15lfa23ia@ieng6.ucsd.edu <enter>```. This command was typed into the terminal to remote connect.

## Step 5:
<img width="784" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/979c0aeb-2434-4cb9-a7e1-eb7d280c896d">

Keys pressed: The ```ls  <enter>``` command was typed into terminal. Followed by a ```cd wa <tab> <enter>``` to change directory into wavlet/ directory. Run the ```rm -rf la <tab> <enter>``` to remove old cloned repository previously in the lab. Go to GitHub, Open old forked repository. Settings -> Delete this Repository. Go to cs15l class repository for lab7. Fork a new repository. Open new forked repository. Code -> SSH -> copy git@github.com:joh048/lab7.git. Run ```git clone  <Ctrl> + <v>```. Press ```<enter>``` to clone new forked repository.

## Step 6:
<img width="803" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/9d4c9644-aa19-4d1f-953f-2fb0c33b1f59">

Key Pressed: Run ```ls <enter>``` command to view current files / directories. Run ```cd la <tab> <enter>``` to change directory into lab7/. Run ```ls <enter>``` command to see if test.sh bash script is present in directory. We will need this to run unit tests. Run ```bash t <tab> <enter>``` to run unit tests. Code is failing in ListExamples.java.

## Step 7: 
<img width="303" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/a5f916e9-67cb-400b-a931-2aa0bc7de2e0">
<img width="383" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/eb412916-7b8a-418d-85e3-9d6528d719db">
<img width="374" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/a39d8ec6-cb07-4334-9259-8808fc91e2c2">

Key Pressed: Run ```vim L <tab> <.> <tab> <enter>``` to edit ListExamples.java file. Press ```<left> <i> <2> <esc> <right> <x>``` to make changes from index1 to index2 in order to fix the failing test. Press ```<:> <w> <q> <enter>``` to save changes and quit vim edittor.

## Step 8:
<img width="362" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/3bd66cb5-233e-4447-8671-b129aeaf0e76">

Key Pressed: Run ```bash t <tab> <enter>``` to run unit tests from the test.sh bash script. Code is now fixed!

## Step 9:
<img width="533" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/249b927d-6fcc-42b7-b3c0-a945d2049bed">
<img width="589" alt="image" src="https://github.com/joh048/cse15l-lab-report-4/assets/146862219/407429a7-4174-409f-836c-b472a2b43115">

Key Pressed: Enter ```git status <enter>``` to check which files has been editted. Only ListExamples.java has been updated. Enter ```git add L <tab> <.> <tab> <enter>``` to add ListExamples.java to be committed. Enter ```git status <enter>``` to check whether file has been added. Enter ```git commit -m "fixing error" L <tab> <enter>``` to commit ListExamples.java. Enter ```git push <enter>``` to push commits to GitHub.






