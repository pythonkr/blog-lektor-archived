# blog.pycon.kr 저장소
[http://blog.pycon.kr](http://blog.pycon.kr)

## 블로그 운영
- 이 블로그는 Lektor 라고 하는 static site generator 로 운영 됩니다.
- Lektor 소개 : [What is Lektor](https://www.getlektor.com/docs/what/)
- Lektor 설치 : [Installation](https://www.getlektor.com/docs/installation/)
 - Mac app을 다운로드 받아서 설치하는 방법, pip로 설치하는 방법 2가지 방법이 있습니다. 어떤 방법을 사용해도 상관이 없습니다.

### 글쓰기 방법 #1: Admin에서 쓰는 방법
1. Lektor desktop 사용해 admin 실행
 - Lektor Mac app 실행
 - 저장소에 있는 project file을 open
 - `view admin panel`(연필 아이콘) 클릭
 - 브라우져에서 뜬 화면에서 글쓰기 ("+"아이콘)
 
2. command line 사용해 admin 실행
 - lektor 설치 디렉토리에서 `$ lektor server` 실행
 - `http://localhost:5000/admin/` 방문
 - 브라우져에서 뜬 화면에서 글쓰기 ("+"아이콘)

### 글쓰기 방법 #2: 직접 `/content`안에 디렉토리를 만들고 .lk 파일을 만드는 방법
 - Lektor 사이트 참고

### 글쓰기 완료후
- 변경 사항을 `master` 브랜치에 git push (또는 리뷰가 필요시 PR로 올림)
- 어드민 우상단에 있는 Publish 버튼(구름모양 아이콘) 클릭해서 변경사항 반영하기
