# 《바이브 코딩, 끝까지 만드는 법》 — 업데이트·정오표·예제 파일

이 페이지는 전자책 《바이브 코딩, 끝까지 만드는 법 — with 클로드 코드》의 독자를 위한 곳입니다. 책은 2026년 10월 화면을 기준으로 썼습니다. 그 뒤에 바뀐 화면, 책에서 틀린 곳, 실습 예제 파일을 여기에 모아 둡니다.

- [업데이트: 책과 화면이 다를 때](#업데이트-책과-화면이-다를-때)
- [정오표: 책에서 틀린 곳](#정오표-책에서-틀린-곳)
- [예제 파일 내려받기](#예제-파일-내려받기)

---

## 업데이트: 책과 화면이 다를 때

AI 도구는 버튼 이름과 메뉴 위치가 자주 바뀝니다. 책의 본문은 바뀌지 않는 원리를 다루고, 바뀌기 쉬운 버튼 이름과 메뉴 경로는 각 장 끝의 **도구 따라 하기** 표에 모아 두었습니다. 그 표와 화면이 다르면 아래 목록을 먼저 확인하세요.

| 날짜 | 장 | 바뀐 것 | 이렇게 하세요 |
|---|---|---|---|
| - | - | 아직 없습니다 | - |

목록에 없는데 화면이 다르다면, 보이는 화면을 그대로 AI에게 설명하고 "책에서는 ○○ 메뉴였는데 지금은 어디에 있어?"라고 물어보세요.

---

## 정오표: 책에서 틀린 곳

| 날짜 | 장·절 | 틀린 내용 | 바른 내용 |
|---|---|---|---|
| - | - | 아직 없습니다 | - |

---

## 예제 파일 내려받기

각 장의 실습을 마쳤을 때의 폴더입니다. 실습 중에 막히면 내 폴더와 비교해 보세요. **15장만은 실습을 시작할 때의 파일**(`chapter15-start`)도 따로 있습니다.

파일 이름을 누른 뒤 오른쪽 위의 내려받기 버튼(↓, Download raw file)을 누르면 됩니다. 받은 zip 파일은 오른쪽 클릭 → '압축 풀기'로 풉니다.

| 장 | 파일 | 들어 있는 것 |
|---|---|---|
| 3 | [chapter03.zip](examples/chapter03.zip) | 가계부 (요청 B로 만든 결과) |
| 5 | [chapter05.zip](examples/chapter05.zip) | 첫 웹페이지 |
| 7 | [chapter07.zip](examples/chapter07.zip) | 예산 기능을 넣은 가계부 + 컨텍스트 팩·프로젝트 지침 글 |
| 9 | [chapter09.zip](examples/chapter09.zip) | 등산 기록장 + 기획서(plan.md, 8장) + 규칙 파일(CLAUDE.md) |
| 10 | [chapter10.zip](examples/chapter10.zip) | 등산 기록장 (작게 나눠 더한 기능) |
| 11 | [chapter11.zip](examples/chapter11.zip) | 등산 기록장 (버그를 고친 뒤) |
| 12 | [chapter12.zip](examples/chapter12.zip) | 등산 기록장 (계획 모드로 고친 뒤) |
| 13 | [chapter13.zip](examples/chapter13.zip) | 등산 기록장 + 테스트(`tests/check_plan.py`) |
| 14 | [chapter14.zip](examples/chapter14.zip) | 등산 기록장 (다른 모델로 검토한 뒤) |
| 15 | [chapter15-start.zip](examples/chapter15-start.zip) | **실습 시작 파일 10개** (가짜 광고 보고서와 잡다한 파일) |
| 15 | [chapter15.zip](examples/chapter15.zip) | 정리된 폴더 + 주간 보고서 자동 생성 |
| 16 | [chapter16.zip](examples/chapter16.zip) | 내 컴퓨터에서 쓰는 광고 대시보드·예산 계산기 |
| 17 | [chapter17.zip](examples/chapter17.zip) | 등산 유형 심리테스트 |
| 18 | [chapter18.zip](examples/chapter18.zip) | 브라우저 게임 '정상까지 달려라' |
| 19 | [chapter19.zip](examples/chapter19.zip) | 광고 문구 도우미 (AI API 연동, 23장 보안 수정까지 반영) |
| 20 | [chapter20.zip](examples/chapter20.zip) | 로그인하는 등산 기록장 (Supabase) |
| 24 | [chapter24.zip](examples/chapter24.zip) | 공개 전 체크리스트를 거친 게임 |
| 25 | [chapter25.zip](examples/chapter25.zip) | 기록을 남긴 폴더와 남기지 않은 폴더 비교 |
| 26 | [chapter26.zip](examples/chapter26.zip) | 버전 관리를 시작한 게임 |
| 27 | [chapter27.zip](examples/chapter27.zip) | 정리한 업무 도구 |
| 28 | [chapter28.zip](examples/chapter28.zip) | 인수인계 문서(HANDOFF.md)를 붙인 로그인 기록장 |
| 29 | [chapter29.zip](examples/chapter29.zip) | 29장에서 살펴본 심리테스트 (17장 결과와 같음) |
| 31 | [chapter31.zip](examples/chapter31.zip) | 회사 제안서(PROPOSAL.md)를 붙인 업무 자동화 |

표에 없는 장은 새로 만드는 파일이 없거나(1·2·4·21·22·30장), 다른 장 예제에 들어 있습니다. 6장은 chapter05.zip에서 시작하고, 8장 기획서는 chapter09.zip에, 23장 수정은 chapter19.zip에 들어 있습니다.

### 받기 전에 알아 둘 것

- **실습 자료는 모두 가짜입니다.** 광고 보고서의 숫자, 회의록, 사람 이름(김하늘 등)은 실습을 위해 만든 것입니다.
- **키와 비밀번호는 들어 있지 않습니다.** 19장과 20장은 내 키를 넣은 `.env` 파일이 있어야 돌아갑니다. 만드는 방법은 책 19장과 20장에 있습니다. 20장의 `public/config.js`도 빠져 있으니, 책대로 내 Supabase 프로젝트 정보로 다시 만드세요.
- **설치 폴더는 빠져 있습니다.** `node_modules`, `.venv`처럼 내려받아 다시 만들 수 있는 폴더는 넣지 않았습니다. 필요하면 Claude Code에게 "이 폴더에 필요한 것을 설치해 줘. 무엇을 설치하는지 먼저 알려 줘"라고 요청하세요.
- **원본은 그대로 두고 복사본에서** 실습하세요. 책의 원칙과 같습니다.
