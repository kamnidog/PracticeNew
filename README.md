"# PracticeNew" 
Вышинский Кирилл
Последовательность команд:
1. mkdir Practice1
2. cd Practice1
3. echo "# PracticeNew" >> README.md
4. git init
5. git add README.md
6. git commit -m "first commit"
7. git branch -M main
8. git remote add origin https://github.com/kamnidog/PracticeNew.git
9. git push -u origin main
10. git checkout -b dz1
11. git add .
12. git commit -m "dz1: Добавил дз по проектированию структуры базы данных"
13. git push -u origin dz1
14. git checkout main и т.д для всех домашних заданий
15. gh pr create --base main --head dz1 --title "DZ1" --body "Вышинский Кирилл,2 курс" (Добавление pull-request)
16. gh pr merge --merge --auto и т.д для всех веток
