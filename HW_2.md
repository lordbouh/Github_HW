# Github_HW2

1. На локальном репозитории сделать ветки для:  
- Postman  
git branch Postman  

- Jmeter  
git branch Jmeter  

- CheckLists  
git branch CheckLists  

- Bag Reports  
git branch Bag_Reports  

- SQL  
git branch SQL  

- Charles    
git branch Charles  

- Mobile testing  
git branch Mobile_testing  

2. Запушить все ветки на внешний репозиторий  
 git push --all  
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/lordbouh/Github_HW.git  
\* [new branch]      Bag_Reports -> Bag_Reports  
\* [new branch]      Charles -> Charles  
\* [new branch]      CheckLists -> CheckLists  
\* [new branch]      Jmeter -> Jmeter  
\* [new branch]      Mobile_testing -> Mobile_testing  
\* [new branch]      SQL -> SQL  
\*ранее уже залил ветку Postman:  
remotes/origin/Bag_Reports  
remotes/origin/Charles  
remotes/origin/CheckLists  
remotes/origin/HEAD -> origin/main  
remotes/origin/Jmeter  
remotes/origin/Mobile_testing  
remotes/origin/Postman  
remotes/origin/SQL  
remotes/origin/main  

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта  
git checkout Bag_Reports  
Switched to branch 'Bag_Reports'  
cat > bug_report.txt  
id 1  
severity low  
title some title here  
STR step 1 step 2 step 3  
ER expected result  
AR actual result  
Environment Windows + Browser  
Attachment file1.jpg  
Comments none  

4. Запушить структуру багрепорта на внешний репозиторий
git add bug_report.txt  
git commit -m "created bug_report file structure"  
git push --set-upstream origin Bag_Reports  
Enumerating objects: 4, done.  
Counting objects: 100% (4/4), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (3/3), done.  
Writing objects: 100% (3/3), 399 bytes | 99.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/lordbouh/Github_HW.git  
f8af3ce..7fcb110  Bag_Reports -> Bag_Reports  
branch 'Bag_Reports' set up to track 'origin/Bag_Reports'.  

5. Вмержить ветку Bag Reports в Main  
git checkout main  
git merge Bag_Reports  
Updating f8af3ce..7fcb110  
Fast-forward  
bug_report.txt | 9 +++++++++  
1 file changed, 9 insertions(+)  
create mode 100644 bug_report.txt  

6. Запушить main на внешний репозиторий.  
git add bug_report.txt  
git commit -m "changes"  
git push  
Enumerating objects: 7, done.  
Counting objects: 100% (7/7), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (3/3), done.  
Writing objects: 100% (3/3), 394 bytes | 131.00 KiB/s, done.  
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0  
remote: Resolving deltas: 100% (1/1), completed with 1 local object.  
To https://github.com/lordbouh/Github_HW.git  
a9fa3fb..d80bd57  main -> main  

7. В ветке CheckLists набросать структуру чек листа.  
cat > checklist.txt  
id 1  
title Some title here  
Environment Windows + Browser  
Status pass or fail  
comment none  

8. Запушить структуру на внешний репозиторий  
git add checklist.txt  
git commit -m "created checklist"  
git push --set-upstream origin CheckLists  
Enumerating objects: 4, done.  
Counting objects: 100% (4/4), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (3/3), done.  
Writing objects: 100% (3/3), 354 bytes | 88.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/lordbouh/Github_HW.git  
f8af3ce..c1b5c4d  CheckLists -> CheckLists  
branch 'CheckLists' set up to track 'origin/CheckLists'.  

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  
comment "created file & push via terminal"  

10. Синхронизировать Внешнюю и Локальную ветки Main  
git pull/fetch  
