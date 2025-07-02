## 🚀 지라 ↔️ 깃헙 자동화 학습 레포지토리 🚀

---

- [x] `git hook`으로 지라 이슈 티켓 넘버 커밋 메시지에 포함
- [x] `git clone` 시 정의한 `git hook` 스크립트를 `.git/hooks` 경로로 복사하기
- [x] github 이슈 생성 시 Jira task 생성 자동화
  - [x] Jira `티켓 번호`로 브랜치 생성
  - [x] 브랜치 생성 시 github 이슈 댓글로 생성된 티켓 번호와 연결된 Jira Task 링크 알림
  - [x] jira task 네이밍 컨벤션을 '[BE/타입] : 이슈 제목' 으로 'BE 키워드' 추가해 '/'로 접두사 부분을 구분하여 생성
  - [x] github 이슈 본문을 파싱하여 Jira task 상세 자동 할당
    - [x] `설명` 자동 할당