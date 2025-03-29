# Git Cheat Sheet

This is a file created to help navigate git. 


## Pushing code
1) Always check your location 

2) Run on the terminal: 

    ``` Pwd```

3) If in correct location run 

    ``` git status ```

4) Then you should see items that have been modified. (Make sure you never commit api keys or private information)


5) Next to the add each item run 
    
    ``` git add <file> ```

6) To check if you added the correct item run: 

     ``` git status ```

7) If you accedently added a file you didn't want to. NO WORRIES!!! run: 
    
    ``` git restore --staged <file> ```
    

8) Check if files are correct
    
     ``` git status ```

9) Check your files status again
    
     ``` git status ```

10) Next check the branch you want to commit to
    
     ``` git checkout ```

11) Next of its all correct, then commit
    
     ``` git push <branch> ```

#### How do you switch Branches 
    git checkout <branch_name>
#### How do you create new Branches 
    git checkout -b <branch_name>
#### How do you see all your branches
    git branch -a




