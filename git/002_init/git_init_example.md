# git init
현재 디렉토리 하위에 .git 디렉토리를 생성. 현재 디렉토리부터 버전관리를 시작한다는 내용.

## github에서 보여주는 기본 

```
echo "# 프로젝트" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/계정명/레파지토리명.git
git push -u origin master
```