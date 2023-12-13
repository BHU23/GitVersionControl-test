git status
git checkout main
git checkout -b issue-2

git add <ไฟล-> หรือ
git rm <ไฟล->

git commit -m “สร0าง Entity - close #2”
git remote update 
git rebase origin/main 

git checkout main # สลับมา main
git merge issue-2 --no-ff # ทำการ merge issue-2 เข1าสู? main

git push origin main
git remote update
git rebase origin/main
git push origin main