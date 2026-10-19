# 19. MCP 용어와 참고표

## 핵심 용어

| 용어 | 쉬운 뜻 | 실무에서 확인할 것 |
| --- | --- | --- |
| MCP | AI와 외부 데이터·도구를 연결하는 공통 규칙 | 사양 버전·호환성 |
| Host | 사용자가 AI를 만나는 앱 | 승인 화면·로그인 |
| Client | Host와 Server 사이의 연결 담당 | 권한·도구 호출 정책 |
| Server | 자료와 도구를 제공하는 프로그램 | 제공자·업데이트·권한 |
| Tool | 검색·작성·변경처럼 실행하는 기능 | 입력·부작용·승인 |
| Resource | AI가 참고하는 문서·데이터 | 출처·최신성·민감도 |
| Prompt | 반복 업무를 시작하는 양식 | 사용자 동의·정책 우선순위 |
| 원격 MCP | 네트워크로 연결하는 서버 | TLS·인증·공급자 |
| 로컬 MCP | 내 컴퓨터나 사내 서버에서 실행 | 파일·프로세스 권한 |
| A2A | 에이전트끼리 작업을 주고받는 프로토콜 | 신원·위임 범위 |
| Tasks | 오래 걸리는 작업의 상태를 다루는 확장 | 진행·취소·재개 |
| 최소 권한 | 필요한 범위만 허용하는 원칙 | 읽기·쓰기·삭제 분리 |

## 연결 전 10문항

1. 이 연결이 해결할 업무 문제는 한 문장으로 말할 수 있는가?
2. 어떤 Resource를 읽고 어떤 Tool을 실행하는가?
3. 읽기와 변경 기능이 분리되어 있는가?
4. 실제 사용자는 누구이며 어떤 권한을 갖는가?
5. 서버 제공자와 소스·업데이트 이력이 확인되는가?
6. 비밀키가 코드·로그·화면에 남지 않는가?
7. 외부 영향 행동에 승인 화면이 있는가?
8. 오류·중단·재시도·복구를 시험했는가?
9. 요청 ID·결과·지연·비용을 추적할 수 있는가?
10. 사고가 나면 연결 해제·토큰 폐기·담당자 전달을 할 수 있는가?

## 공식 참고 자료

- [MCP 공식 사이트](https://modelcontextprotocol.io/)
- [MCP 사양](https://modelcontextprotocol.io/specification)
- [MCP 공식 블로그](https://blog.modelcontextprotocol.io/)
- [MCP 2026-07-28 사양 변경](https://blog.modelcontextprotocol.io/posts/2026-07-28/)
- [MCP 공식 레지스트리](https://registry.modelcontextprotocol.io/docs)
- [Agentic AI Foundation](https://aaif.io/)
- [A2A 프로토콜 도입 현황](https://www.linuxfoundation.org/press/a2a-protocol-surpasses-150-organizations-lands-in-major-cloud-platforms-and-sees-enterprise-production-use-in-first-year)

## 집필 기준일

이 책의 최신성 기준일은 **2026년 10월 19일**입니다. 제품별 연결 화면과 SDK 사용법은 변경될 수 있으므로, 실제 도입 전 반드시 해당 제품과 MCP 공식 문서를 다시 확인합니다.

