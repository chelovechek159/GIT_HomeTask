# GIT_HomeTask2

#### 1. На локальном репозитории сделать ветки для:
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
    
 

#### 2. Запушить все ветки на внешний репозиторий

    git push -u origin Postman
    git push -u origin Jmeter
    git push -u origin CheckLists
    git push -u origin Bug_Reports
    git push -u origin SQL
    git push -u origin Charles
    git push -u origin Mobile_Testing

#### 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
    git checkout Bug_reports    
    cat > Bug_report.txt ---> BR Structure ---> control + c    

#### 4. Запушить структуру багрепорта на внешний репозиторий
    git add .
    git commit -m 'text'
    git push
#### 5. Вмержить ветку Bag Reports в Main

    git checkout main
    git merge Bug_reports


#### 6. Запушить main на внешний репозиторий.

    git push

#### 7. В ветке CheckLists набросать структуру чек листа.

    git checkout CheckLists
    cat > checklist.txt


#### 8. Запушить структуру на внешний репозиторий

    git add .
    git commit -m "text"
    git push

#### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

    Compare & pull request ---> create pull request ---> Merge pull request ---> confirm merge

#### 10. Синхронизировать Внешнюю и Локальную ветки Main

    git checkout main
    git pull

