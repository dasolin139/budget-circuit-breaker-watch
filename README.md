# Budget Circuit Breaker Watch

AI 에이전트/SDK 운영 중 무음 hang, runaway loop, cache hit 급락, background 작업 전면 실패 같은 이상 징후를 운영자용 incident brief와 circuit breaker 기준으로 바꿔주는 초경량 공개 MVP입니다.

## 핵심 대상
- OpenAI Responses API / Agents SDK / LangChain / 자체 orchestrator 운영팀
- 비용 폭주와 무음 실패를 동시에 관리해야 하는 개발팀/운영자

## 측정 수단
- 점검안 생성 클릭
- 복사 클릭
- 문의 메일 클릭

## 외부 근거
- https://github.com/openai/openai-python/issues/3054
- https://github.com/openai/openai-agents-python/issues/2838
- https://community.openai.com/t/caching-rate-drop-after-switching-to-responses-api/1370788
- https://community.openai.com/t/responses-api-background-true-returning-server-error-on-all-requests-2026-03-13/1376674
- https://community.openai.com/t/responses-api-bug-answer-is-to-previous-question-in-conversation/1369499
- https://news.ycombinator.com/item?id=47112543
