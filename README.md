# Quiz

```
cd C:\Users\IME16\Desktop\PatternRecognition # Pattern Recognition 폴더로 이동

git clone https://github.com/min942773/Quiz.git # github에 생성한 Quiz repository를 clone한다

cd Quiz # 만들어진 Quiz 폴더로 이동

git add . # 20190924_Quiz.py 파일과 20190930_Quiz2_solution.py를 add한다

git commit -m "Add Quiz and Quiz2" # 위의 두 파일을 commit한다

git branch solution # solution 브랜치 생성

git checkout solution # solution 브랜치로 이동

git add . # 20190924_Quiz.py를 수정하여 20190924_Quiz_solution.py 파일을 만든 뒤 이를 add함

git commit -m "Edit Quiz1 and Make Quiz1_sliution" # 위 파일 수정 내용을 commit함 (sliution -> solution 오타입니다...)

git push origin solution # 원격 저장소에 새로만든 branch를 push 함

git checkout master # master 브랜치로 이동

git push # master 브랜치가 깃허브에서 사라져있어 다시 push해 master 브랜치를 원격저장소에 만들어줌

git merge solution # master 브랜치에 solution 브랜치를 머지함

git push origin --delete solution # solution 브랜치 원격저장소에서 삭제

git branch -d solution # solution 브랜치 로컬에서 삭제
``` 
