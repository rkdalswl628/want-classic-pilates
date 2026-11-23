WANT CLASSIC PILATES 무료 홈페이지 + 관리자 편집 준비 파일

이 폴더는 Netlify(무료 정적 호스팅) + GitHub(파일 저장소) + Pages CMS(무료 관리자 편집 화면)를 사용하도록 준비되어 있습니다.

중요: 파일만 업로드했다고 웹사이트나 관리자 계정이 자동 생성되는 것은 아닙니다. 아래 1회 초기 연결을 해야 합니다.

1) GitHub 계정 만들기: https://github.com/
2) GitHub에서 New repository를 눌러 want-classic-pilates 라는 저장소를 만듭니다. 가능하면 Public으로 설정합니다.
3) 이 ZIP 압축을 풀고, 폴더 안의 파일과 폴더(index.html, .pages.yml, content, media)를 저장소 최상위에 업로드합니다. ZIP 파일 자체를 저장소에 올리는 것이 아닙니다.
4) Netlify 가입: https://app.netlify.com/signup
   Add new project -> Import an existing project -> GitHub -> 방금 만든 저장소 선택 -> Publish.
   배포가 끝나면 xxxx.netlify.app 형태의 무료 주소가 나옵니다.
5) Pages CMS 관리자 연결: https://app.pagescms.org/
   GitHub로 로그인 -> GitHub App 설치/권한 승인 -> want-classic-pilates 저장소 선택.
   저장소 루트의 .pages.yml을 읽으면 Homepage content 편집 항목이 나타납니다.
6) Homepage content에서 사진, 원장 소개, 프로그램, 주소, 운영시간, 전화, 인스타그램/상담 링크를 수정하고 Save 합니다.
   Pages CMS가 GitHub 저장소의 파일을 수정합니다. Netlify가 GitHub 변경을 감지해 홈페이지를 다시 배포합니다.

사진 올리기: Pages CMS의 Homepage content에서 Main studio photo / About photo / Location photo를 눌러 업로드하세요.

주의:
- .pages.yml 파일 이름 맨 앞의 점(.)을 유지하세요.
- 주소/전화/운영시간/기구는 실제 정보로 바꾼 뒤 공개하세요.
- Pages CMS는 GitHub 저장소를 편집하므로 GitHub 계정과 Pages CMS 권한을 안전하게 관리하세요.
- 기본 사이트 주소는 무료입니다. 개인 .com 도메인은 별도 구매 비용이 듭니다.
- 무료 플랜 조건과 기능은 서비스 정책에 따라 바뀔 수 있습니다.

관리자 페이지: https://app.pagescms.org/
공식 설정 안내: https://pagescms.org/docs/quick-start/
Netlify 저장소 배포 안내: https://docs.netlify.com/start/quickstarts/deploy-from-repository/
