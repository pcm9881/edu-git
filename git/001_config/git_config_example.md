# git config
git config란 내가 현재 사용하는 깃에 대한 설정에 대한 명령어

## 계정 설정

```
git config --global user.name "유저이름"
git config --global user.email "유저이메일"
```

## 현재 내 git config 

```
git config --list
```

## 맨처음 계정 설정

```

```

## 윈도우와 맥 line ending
서로 다른 OS 환경 commit 이나 merge 시 문제를 야기할 수 있다.

윈도우(window) | 맥(mac)
---|---
CR(Carriage-Return, \r) |  LF(Line Feed, \n)

## 윈도우만 진행

```
git config --global core.autocrlf true
```