# Git 명령어 정리
## 1️⃣ 저장소 설정
- `git init`: 로컬 저장소 초기화.
- `git config --global user.name "사용자 이름"`: 사용자 이름 설정.
- `git config --global user.email "사용자 이메일"`: 사용자 이메일 설정.

## 2️⃣ 파일 추가 및 커밋
- `git add <파일명>`: 변경된 파일을 스테이징 영역에 추가.
- `git commit -m "메시지"`: 스테이징된 파일을 로컬 저장소에 커밋.

## 3️⃣ 원격 저장소 작업
- `git remote add origin <URL>`: 원격 저장소 연결.
- `git push origin main`: 로컬 변경 사항을 원격 저장소로 업로드.
- `git pull origin main`: 원격 저장소에서 최신 변경 사항 가져오기.
