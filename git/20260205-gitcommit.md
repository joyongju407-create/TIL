📌 Git & GitHub 컨벤션 치트시트
1. 커밋 메시지 말머리 (Commit Message Prefixes)
커밋 제목 맨 앞에 붙여서 "무슨 작업을 했는지" 한눈에 보여주는 태그입니다. (작성법: 태그: 내용)

[코드 변경 O]

Feat = 새로운 기능 구현 (Feature)

Fix = 버그 수정

Refactor = 결과는 같지만 코드 구조를 개선 (리팩토링)

Perf = 성능 개선 (Performance)

[코드 변경 X]

Docs = 문서 수정 (README, 주석 등)

Style = 코드 포맷팅 (띄어쓰기, 세미콜론 등 로직 변경 없음)

Test = 테스트 코드 추가/수정

Chore = 설정 파일 변경, 패키지 설치 등 잡일

2. 이슈 자동 종료 키워드 (Closing Keywords)
커밋 메시지나 PR 내용에 적으면, Merge 될 때 해당 이슈(#번호)를 자동으로 닫아주는 명령어입니다. (작성법: 키워드 #이슈번호)

[3대장 (기능은 모두 동일)]

Close / Closes / Closed = 가장 일반적으로 닫을 때 사용

Fix / Fixes / Fixed = 버그를 고치고 닫을 때 주로 사용

Resolve / Resolves / Resolved = 문의나 요청사항을 해결했을 때 사용

📝 사용 예시 (Example)
Plaintext
# 커밋 메시지 예시
Feat: 로그인 페이지 구현
Docs: README에 실행 방법 추가

# PR 내용 예시
이번에 로그인 버그를 수정했습니다.
Fixed #3  <-- (3번 이슈 자동 종료됨)
