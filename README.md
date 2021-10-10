# git-exercises

# Scenario-1

1. Created a personal git repository on gitlab by the name of git-exercise using UI.
2. Working on "main" branch.

3. Then, using 'git clone https://gitlab.com/saumyalavania97/git-exercises.git' I cloned the whole project.

# Scenario-2

4. 'mkdir saumya'
   new empty folder
5. 'cd saumya' --> 'type nul > my_name.txt'
   text file created
6. 'echo My name is saumya sharma > my_name.txt'
   content added to the text file
7. 'git add . --> git commit -m "added text file" --> git push'
   commiting the file

# Scenario-3

8. 'git branch exercise/conflict-resolution' --> creating new branch
9. 'git checkout exercise/conflict-resolution' --> switched to another branch
10. and then change previous text to "My name used to be saumya sharma" in new branch
11. 'git commit -am "updated text file"' --> 'git push origin exercise/conflict-resolution' --> added and commited change in one line
12. 'git checkout main' --> and then change text to "My name has always been saumya sharma" in main branch
13. 'git commit -am "updated text file in main"' --> 'git push origin main' --> commiting the changes
14. Raised a merge request to merge the exercise/conflict-resolution branch to the master/main branch at Gitlab UI
15. We have two options to merge the branches
    i) using inline editor (edit inline) and then do the needed changes, or
    ii) using terminal:
    switch to new branch using 'git checkout exercise/conflict-resolution' -->
    then fetch and merge the changes from main to new branch using 'git pull origin main'
    Now in code editor make the required changes like in our case we required both the changes so click on 'both changes'
    and commit the changes using 'git commit -am "conflict resolved"' --> 'git push origin exercise/conflict-resolution'
    now go to gitlab UI and merge the branches in merge request section and source branch has been deleted when we choose that option along with merge request.
16.
