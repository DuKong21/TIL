# 분산관리

## 중앙 집중

버전관리가 쉬움

## 분산형 

블록체인, 정보의 진위 여부 판별 가능

## git

분산 버전 관리 시스템

특정 버전을 남긴다 = **커밋**한다

#### 커밋

##### working Directory

- 내가 작업하고 있는 실제 디렉토리

##### Staging Area

- 커밋으로 남기고 싶은, 특정 버전으로 관리하고 싶은 파일이 있는곳

##### Repository

- 버전별로 기록하는 디렉토리 (커밋들이 저장되는곳) 

### 깃 명령어

ls - 현재 위치 파일 목록

cd - 현재 위치 파일 이동

cd .. - 현재 폴더의 상위 폴더로 이동

mkdir - 폴더 생성

rm -r - 폴더 삭제

touch - 파일 생성

rm - 파일 삭제

git init - 디렉토리 버전 관리 생성

git add 파일이름 or . - working Directory에서 Staging Area으로 남김

git commit -m " " - 커밋

git status - 커밋 확인

git log - 커밋 로그 출력

git config --global user.email " "  - 깃 이메일 

git config --global user.name " "  - 깃 닉네임

code . - vscode 바로 열기

git diff (A) (B) - 커밋 비교

git remote rm origin 

git remote add origin (링크) - 깃허브와 깃 연결

git push -u origin (A) - (A)에 있는 모든 커밋들은 origin깃허브에 업로드

(A) - ex) master

git clong{} - 레포지토리에 있는걸 로컬로 복사 

git push - clong 사용했을때 가능 

## git hub

깃 기반 홈페이지

