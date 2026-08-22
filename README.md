# 조혁준 | 자동화 기반 AI 에이전트 개발자

재사용 가능한 구조와 자동화로 반복적인 시간 투자를 줄이고,
애플리케이션부터 클라우드 인프라, 배포와 모니터링까지 파고드는
AI 에이전트 개발자입니다.

문제는 단편 수정에 그치지 않고 DEV 환경에서 적용해 목적을 확인하고,
적합하면 유지하고 아니면 다른 방법을 찾아 반복합니다.
팀에는 재사용 가능한 구조와 한 번의 실행으로 끝나는 자동화를 남깁니다.

[Email](mailto:johj101159@gmail.com) · [GitHub](https://github.com/j5hjun)

---

## 주요 역량

| 영역 | 구체적인 경험 |
| --- | --- |
| AI Agent & Automation | MCP 도구 계약, CLI·MCP 실행 구조 통합, 브라우저 세션 관리, 실패 복구와 실제 계정 검증 |
| Backend | OAuth 인증, 암호화 토큰 저장, REST API 프록시, PostgreSQL, 계층 분리와 자동화 테스트 |
| Cloud & DevOps | AWS·GCP 하이브리드 구성, Terraform, GitHub Actions 배포·롤백, 통합 모니터링 |

---

## 프로젝트

### [Growful SmartThings Gateway](./project/growful.md)

**Backend · Integration · DevOps**

SmartThings OAuth 인증부터 토큰 저장, API 프록시와 연결 해제까지 구현한 개인 프로젝트입니다.

- 기간: 2026.07
- 형태: 개인 프로젝트
- 역할: 백엔드 설계와 구현, OAuth 연동, 테스트, private beta 배포
- 결과: OAuth 전체 흐름, 토큰 암호화·교체, `/v1/*` 프록시와 계층별 자동화 테스트 구축

[상세 사례](./project/growful.md) ·
[Repository](https://github.com/j5hjun/growful) ·
[Service](https://smartthings.growful.click)

### [K-Commerce](./project/k-commerce.md)

**AI Agent · Backend · Automation**

쿠팡의 주문, 상품, 장바구니와 리뷰 작업을 CLI와 MCP 도구로 제공한 커머스 자동화
프로젝트입니다.

- 기간: 2026.06–2026.07
- 형태: 3인 협업
- 역할: 공통 도구 계약, 로그인과 세션, 주문·상품 자동화, Python 패키지 배포
- 결과: 팀이 구현한 21개 도구가 CLI와 MCP에서 같은 요청·응답 계약을 사용하도록 통합

[상세 사례](./project/k-commerce.md) ·
[Repository](https://github.com/j5hjun/k-commerce) ·
[My Pull Requests](https://github.com/j5hjun/k-commerce/pulls?q=is%3Apr+author%3Aj5hjun)

### [CareerBee Cloud](./project/careerbee-cloud.md)

**Cloud · DevOps · Observability**

IT 구직자 대상 웹서비스의 AWS와 GCP 하이브리드 개발 환경, 배포 자동화와 모니터링을
구축한 프로젝트입니다.

- 기간: 2025.03–2025.08
- 형태: 6인 협업, 인프라 2인
- 역할: DEV 인프라, 멀티 클라우드 네트워크, Terraform, CI/CD, 모니터링
- 결과: 서비스별 배포와 자동 롤백, 환경 생성·삭제·복원, AWS·GCP·GPU 관측 통합

[상세 사례](./project/careerbee-cloud.md) ·
[Repository](https://github.com/100-hours-a-week/3-team-CareerBee-cloud) ·
[My Commits](https://github.com/100-hours-a-week/3-team-CareerBee-cloud/commits/develop/?author=j5hjun)

---

## 오픈소스 기여

### [oh-my-opencode-slim](./project/oh-my-opencode-slim.md)

사용할 수 없게 된 Gemini 3 Pro 모델 참조를 3.1 Pro 계열로 갱신했습니다. Provider 설정,
설치 과정, 테스트와 문서를 함께 수정하고 프로젝트 검증 절차를 통과한 뒤 upstream에
병합했습니다.

[기여 내용](./project/oh-my-opencode-slim.md) ·
[Pull Request #143](https://github.com/alvinunreal/oh-my-opencode-slim/pull/143)

---

## 기술

| 분류 | 기술 |
| --- | --- |
| Languages | Python, TypeScript, Shell |
| Agent & AI | MCP, FastMCP, LangChain, OpenAI API |
| Backend | FastAPI, Fastify, PostgreSQL, Kysely, Zod |
| Testing | pytest, Vitest, Playwright |
| Automation | CLI, nodriver, Browser Automation |
| Cloud | AWS, GCP, Cloudflare |
| Infrastructure | Terraform, Docker, Docker Compose, Nginx |
| CI/CD | GitHub Actions, ECR, PyPI |
| Observability | Prometheus, Grafana, Loki |
| Network | Site-to-Site VPN, Tailscale |
