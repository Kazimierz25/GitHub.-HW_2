# GitHub.-HW_2

1. На локальном репозитории сделать ветки для:

 : git branch
- Postman        : git branch Postman
- Jmeter         : git branch Jmeter
- CheckLists     : git branch CheckList
- Bug Reports    : git branch Bug_Reports
- SQL            : git branch SQL
- Charles        : git branch SQL
- Mobile testing : git branch Mobile_testing
 : git branch

2. Запушить все ветки на внешний репозиторий : git push -u origin --all

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта : git checkout Bug_Reports
                                                                            : cat >> Bug_Reports_new.txt
                                                                              Ввод


4. Запушить структуру багрепорта на внешний репозиторий : git add .
                                                        : git commit -m "add Bug_Report_new"
                                                        : git push

5. Вмержить ветку Bag Reports в Main : git checkout main
                                     : git merge Bug_Reports -m "merge Bug_Reports"

6. Запушить main на внешний репозиторий : git commit -am "merge Bug_Reports"
                                        : git push

7. В ветке CheckLists набросать структуру чек листа. : git checkout CheckList
                                                     : vi Checklist.txt
                                                     : Ввод


8. Запушить структуру на внешний репозиторий : git status
                                             : git add Checklist.txt
                                             : git commit -m "add Checklist"
                                             : git push


9. На внешнем репозитории сделать Pull Request ветки CheckLists в main : https://github.com/Kazimierz25/GitHub.-HW_2/tree/CheckList
                                                                       : Pull request
                                                                       : Compare and pull request
                                                                       : CheckList > main
                                                                       : Create pull request
                                                                       : Merge pull request
                                                                       : Confim merge


10. Синхронизировать Внешнюю и Локальную ветки Main : git checkout main
                                                    : git fetch
                                                    : git merge
