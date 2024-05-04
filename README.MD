#GitHub 사용법 정리 

##README.MD 꾸미기 H2

### MARKDOWN HEADER 꾸미기

```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

### CODE 입력방법 

<```> <KOTILIN>
<ANY CODE>
<```>
<>를 생략하는 방식으로 사용한다 

### 수평선 <hr/>

```
* * *

***

*****

- - -

---------------------------------------
```

적용예시

* * *

***

*****

- - -

---------------------------------------

## GIT 기본명령어 다루기 


###기본명령어 

현재 상태 확인
```
git status
```

전체 로그 확인
```
git log
```



저장소 복제 및 다운로드 
```
git clone [https:~]
```

저장소에 코드추가 
```
git add

git add *
```
커밋에 파일의 변경 사항을 한번에 모두 포함 
```
git add -A 
```
커밋 생성
```
git commit -m"message"
```
원격 저장소 변경 내용 디렉으로 가져오기 (pull)
```
git pull
```


### 브랜치 관련 

git 저장소 생성하기 <- git에 올릴때 제일 먼자 하는것 
.git 이라는 파일이 생성됨
```
git init 
```
github 주소와 연결 
```
git remote add origin [github주소]
```
브랜치 생성
```
git branch[브랜치명]
```
브랜치 이동
```
git checkout [브랜치명]
```
브랜치 확인
```
git branch
```
모든 브랜치 확인
```
git branch -a
```
모든파일 add
```
git add.
```
커밋
```
git commit-m"commit message"
```
원하는 브랜치로 push해 원격서버에 전송
```
git push origin [브랜치 이름]
```
브랜치 삭제
```
git branch -d [브랜치 이름]
```
현재 브랜치에 다른 브랜치 수정사합 병합
```
git merge [다른 브랜치 이름]
```

### config 설정 관련 

전체 config 리스트 확인
```
git config --list
```
config 설정하는 방법
-자기가 누구인지 나타내는 것
```
git config --global user.name "한만욱"
git config --global user.email"hanmw110@naver.com"
```
