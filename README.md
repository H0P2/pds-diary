# 플랜두씨 다이어리 · ALEPH T06

공개 결과물: https://pds-diary-hope-20261008.mo990025.chatgpt.site/

`pds-source.zip`은 공개 앱 버전 2 전체 소스입니다. 압축을 풀면 app/, components/, db/, drizzle/, contracts/, scripts/ 및 의존성 잠금 파일과 설정이 원래 경로로 복원됩니다.

- 구현: React + Vinext, Cloudflare D1 SQLite.
- DB 계약: ZIP 내부 contracts/pds-schema-v2.json.
- 시간 입력: 달·주·시간·분·초, 초 정밀도. 1달은 예상 시간 환산 시 30일.
- 로컬 실행: Node 22.13+에서 npm ci 후 npm run dev. D1 바인딩 및 drizzle SQL 적용 필요.
- 단위/저장 검증: node scripts/test-duration.mjs (Node SQLite 지원 필요).
- 빌드: npm run build.
- Sites 소스 커밋: 2b742878446b8c4add0bda7052599018778980cd.

사용자가 정한 실제 계획은 과제 7~13번을 2026-10-08~22의 2주 동안 최우선으로 진행하는 것입니다. 각 과제는 별도 할 일이며 과제당 이틀 간격 임시 마감일을 지정했습니다. 작업량 추정과 실제 실행 시간은 전체 일정 기간과 구분합니다.

실제 실행 기록은 아직 0건입니다. T06-C80(실제 실행 3건 이상)은 미충족이며 실제 시간은 임의로 작성하지 않았습니다. 개발 검증용 자료는 사용자 실행 기록에 포함하지 않습니다.

ZIP에는 개인 실행 데이터, 로컬 데이터베이스, 인증 정보와 비밀값을 포함하지 않습니다.
