# git add

## 단일 파일

```
echo "# add test" >> a.txt
git add a.txt
```

## 다중 파일 

```
echo "# add test2" >> b.txt
echo "# add test3" >> c.txt
git add .
```

## 특정 다중 파일 조건

```
echo "# add test4" >> d.txt
echo "# add test5" >> e.txt
git add *.txt
```

* : asterisk 이라고 한다. 보통 전체허용을 의미한다. 

