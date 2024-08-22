# 2.18 Assignment 01 GIT Workflow

<br>
<strong>Problem</strong>
In a newly created repository, demonstrate the ability to change a file from untracked status to tracked and later unstage the file so that it becomes "untracked" again.
<br>
<strong>Solution</strong>

Step: 1  create a file example.txt<br>
Step: 2  Check the status, git will show untracked files.<br>
Step: 3  Now Add file to stagging area with $ git add example.txt<br>
Step: 4  Check the status, git will show tracked files.<br>
Step: 5  Commit the file for screenshot in the history by $ git commit -m "Initial Upload example.txt file"<br>
Step: 6  Now remove from file stagging area so that it becomes untracked again. with $ git rm --cached example.txt<br>
Step: 7  Check the status, git will show deleted example.txt from staged area and VsCOde will show U denoted Untracked file.<br>
Step: 8 Check your log for history $ git log --oneline<br>
<br>
<br>
End of assignment.
<br>
Author: Shashank Naithani
