# GIT_HomeTask2

#### 1. On the local repository, make branches for:
+ **Postman** 
+ **Jmeter**
+ **CheckLists**
+ **Bug Reports**
+ **SQL**
+ **Charles**
+ **Mobile testing**
######
    git branch Postman
    git branch Jmeter
    git branch CheckLists
    git branch Bug_Reports
    git branch SQL
    git branch Charles
    git branch Mobile_Testing
    
 

#### 2. Push all branches to an external repository

    git push -u origin Postman
    git push -u origin Jmeter
    git push -u origin CheckLists
    git push -u origin Bug_Reports
    git push -u origin SQL
    git push -u origin Charles
    git push -u origin Mobile_Testing

#### 3. In the `Bug Reports` branch, make a text document with the structure of a bug report
    git checkout Bug_reports    
    cat > Bug_report.txt ---> BR Structure ---> control + c    

#### 4. Push the `bug report structure` to an external repository
    git add .
    git commit -m 'text'
    git push
#### 5. Merge the `Bug Reports` branch into `Main`

    git checkout main
    git merge Bug_reports


#### 6. Push `main` to external repository

    git push

#### 7. In the `CheckLists` branch, write the structure of the checklist

    git checkout CheckLists
    cat > checklist.txt


#### 8. Push structure to external repository

    git add .
    git commit -m "text"
    git push

#### 9. On an external repository, make a Pull Request of the `CheckLists` branch in `main`

    Compare & pull request ---> create pull request ---> Merge pull request ---> confirm merge

#### 10. Synchronize External and Local branches `main`

    git checkout main
    git pull

