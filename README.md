스프링 시큐리티 완전정복 강좌 예제입니다.

# 기존 프로젝트를 git repository에 연결 하기


# 1.기존 프로젝트 폴더 내에 진입 
### ex: cd /java/security 

# 2. git 초기화
### git init

# 3. 프로젝트를 연결 할 github repository 생성
### README 파일을 생성하면 최초 커밋 시 파일 기록이 달라서 오류발생할 확률 있음.
### 첫 Commit Push 는 force push 로 에러 해결

# 4. repository 연결
### git remote add origin git@github.com:XXXXXXXX/PortFolio.git

### 연결된 repo 확인 (fetch / push 주소 확인)
### git remote -v

# 5. repository 원격 브랜치로 commit, push 하기 (파일 업로드)
### git add .
### git commit -m '첫번째 커밋'
### git push origin main


