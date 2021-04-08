# My first git project
This is a test project for my own learning purpose.  
Based on https://projects.raspberrypi.org/en/projects/getting-started-with-git 

# Revisiting this especial moment...
When I was learning git and version control s2  
And then I realize that I would like to change the name master to main as I do in every project when I arrive.  
So I also like to leave here the steps just in case:


```bash
git branch -m master main # step 1: Move the ‘master’ branch to ‘main’  
git push -u origin main # step 2: pushing to remote repo  
git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main # step 3: pointing HEAD to main branch  
# step 4: changing on github the default branch https://docs.github.com/en/github/administering-a-repository/changing-the-default-branch  
git push origin --delete master # last step: get rid of the master named branch on the remote repo
```

# References:  
https://stevenmortimer.com/5-steps-to-change-github-default-branch-from-master-to-main/  
https://docs.github.com/en/github/administering-a-repository/changing-the-default-branch 
