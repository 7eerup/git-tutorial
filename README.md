# 깃 튜토리얼

## 깃 버전 확인
```
git -v
git --version
```

## 깃 전역 설정
```
git config --global user.name "user-name"
git config --global user.email "user-email"
```

## 깃 사용자 설정 이름 & 이메일 확인
```
git config --global user.name
git config --global user.email
```

## 초기화
```
git init
```

## 깃 상황 체크
```
git status
```

## 변경 사항 더하기
```
git add .
git add -A
git add --all
```

## 변경 사항 이전 되돌리기 to unstage
```
git rm --cached <file>
```

## 변경 사항 적용 커밋
```
git commit -m "commit message"
```

## 브랜치 main 설정
```
git branch -M main
```

## 깃허브 저장소 연결
```
git remote add origin https://github.com/7eerup/git-tutorial.git
```

## 변경 사항 푸시
```
git push -u origin main
```

## 로그 기록 확인
```
git log
```

## 이전 상태 되돌리기
```
git reset 커밋No.8d7a51 --hard   ex) commit No.8d7a51308bee0c368a08913e7791480b8c55d351
git revert
```

## 삭제 파일 되돌리기
```
git restore <file>
```

> * <a href="https://github.com/7eerup/git-tutorial.git">git-tutorial</a>