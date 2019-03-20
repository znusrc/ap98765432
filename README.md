# HOW TO CREATE YOUR CLASS PROJECT ON GITHUB
Help to **Advance Programming** students.


1. Open the **git bash**.



2. Go to the workspace path using `ls` and `cd`commands. 

   For example: `cd /d/myworkspace`



3. Run this command to clone this project in your workspace.

   `git clone https://github.com/znusrc/ap98765432.git`


4. Rename the _ap98765432_ directory id part name to yorself student number. For example if student number equal to _96765636_ then use this command `mv ap98765432 ap96765636`



5. Open your IDE and open cloned project path as an exist project.



6. Append your codes to the project (complete assignmets packages).



7. To commit and push your project in your account run these commands from **git bash**:

   (suppose git account name is equal to _MyGitAccount_ and student number is equal to _96765636_)

* `git remote set-url origin git@github.com:MyGitAccount/ap96765636.git`

* `git add .`

* `git commit -m "Assignment1 complete."`

* `git push -u origin master`
