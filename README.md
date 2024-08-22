# 2.18 Assignment 01 GIT Workflow

<br>
<strong>Problem</strong>
In a newly created repository, demonstrate the ability to change a file from untracked status to tracked and later unstage the file so that it becomes "untracked" again.
<br>
<strong>Solution</strong>

Step: 1  create a file example.txt
Step: 2  Check the status, git will show untracked files.
Step: 3  Now Add file to stagging area with $ git add example.txt
Step: 4  Check the status, git will show tracked files.
Step: 5  Commit the file for screenshot in the history by $ git commit -m "Initial Upload example.txt file"
Step: 6  Now remove from file stagging area so that it becomes untracked again. with $ git rm --cached example.txt
Step: 7  Check the status, git will show untracked files.
Step: 8 Check your log for history $ git log --oneline


End of assignment.

Author: Shashank Naithani