# GitHub Tutorial

_by Amanda Rivera_

---
## Git vs. GitHub
Git takes snapshots of code you dont github as Github is a place to store code as well as  
collaberate and git is necessary for github.
        


---
## Initial Setup
**Follow the directions below to set up a github account**  
1. Open google tab
2. go to [github.com](www.github.com) and click Sign up
3. Create a username and password as well as put in your email
4. Check your email and verify github
5. On another tab go to [c9.io](c9.io) & click on the gear symbol on the right hand corner & click connected service
(this will connect github to cloud9 and now whenever you sign into c9 click on the cat symbol)
6. Go to main page on github/ top right hand corner click on profile icon and click settings
7. On your left there is a side bar, click on SSH and GPG/ click on new SSH key
8. Title it cloud9
9. go to your cloud9 and on the top right hand click on the gear icon
10. click on the SSH key tab and copy and paste the _2nd_ SSH key into github(it starts with _ssh-rsa_)
## Repository Setup
These steps are a few that you will become experts at because it becomes repetitive. (These steps all go into the blue box at the bottom of the c9)
1. Go into your c9 account 
2. Type `cd ~/workspace` this will make sure you are out of any files and back to basically the home page of cloud 9
3. Type `mkdir first-rep` this will create a directory then type `cd first-repo`
***whenever you make a directory make it a habit to go into it right after***
4. Type `git init` (this initilizes git and gets everything ready to be used) 
 ***now to create a README file***  
5. go to _github_, on the top right hand click on the plus and down arrow icon and click _New Repository

7. Type `touch README.md` and then open it (you could either click on it or type `touch README.md` again)  
 _In order for you to save and add to the staging area a change need to occur_ 
8. In the README.md file write a commit 
9. click back on the bash and type in either `git add .` or `git add README.md` either one will add your change to the staging area
10. then you commit it, now with that you need a smart commit message basically explaining what exactly you have done(make sure it is in present tense).
  ex: _create first readme_
  - type `git commit -m"(insert your commit message)" `



---
## Workflow & Commands
whenever you are coding after you complete one to two coding commands do :
  - `git status` (this is checking to make sure your changes are commited correctly)
to add 
   - `git add .` or ` git add (then the file name) `
to commit 
   - ` git commit -m" (commit message)" `
to push 
   - `git push


---
## Rolling Back Changes