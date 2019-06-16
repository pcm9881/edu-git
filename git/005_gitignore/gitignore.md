# gitignore 제외 
.gitignore 파일 생성

## 예시
```
vi .gitignore
.DS_Store
```
.DS_Store : Mac-OSX 폴더에 접근시 메타데이터를 저장하는 파일이다

## 특정경로 
- 특정경로 만들기

```
mkdir tmp
cd tmp
echo "# 404 file" >> skip.md
cd ..
```

- .gitignore 추가

```
vi .gitignore
/tmp
:wq
```

## 특정확장자 .a
```
vi .gitignore
*.a
:wq
```


## 특정확장자중에 lib.a 파일만 필요하다
```
vi .gitignore
!lib.a
:wq
```
