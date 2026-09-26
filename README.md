# 강민정 · Minjeong Kang

운영 현장에서 반복되는 문제를 발견하고, 작게 만들어 검증하는 AI Product Builder입니다. 상담원이 근거를 확인할 수 있는 AI 도구, 업무 자동화, 데이터 화면에 관심이 있습니다.

## 대표 프로젝트

| 프로젝트 | 해결하려는 문제 · 구현 | 상태 |
|---|---|---|
| [CineWave 상담 코파일럿](https://github.com/EXPOIR0405/helpdesk-copilot) | 가상 OTT 고객센터의 정책 문서를 검색하고, 근거가 없거나 준비 중인 정책이면 확정 답변을 막는 상담 도구. TypeScript, OpenAI, Supabase pgvector, Vitest | **공개 데모** · 가상 데이터 42문항 평가. [설계·평가 기록](https://github.com/EXPOIR0405/helpdesk-copilot#readme) |
| [Webtoon Guard](https://github.com/EXPOIR0405/webtoon-guard) | 웹툰 작가가 저작권 침해 피해 내용을 정리하고 PDF로 출력하는 웹 도구. Next.js, React, Tailwind CSS | **이전 프로젝트** · 피해 신고 기능은 README에서 개발 중으로 표시 |
| [Ad to Pedro](https://github.com/EXPOIR0405/AdToPedro) | 웹 광고를 이미지로 바꾸는 Chrome 확장 프로그램. DOM 조작과 주기적 이미지 교체 | **개인 실험** · 일부 사이트의 스크롤 버그를 README에 명시 |
| [Netflix Content Insight Dashboard](https://github.com/EXPOIR0405/netflix-dashboard) | 공개 Netflix 제목 데이터를 Looker Studio와 Google Sheets로 시각화 | **학습 프로젝트** · 공개 데이터 기반 |
| [Tales of Balder](https://github.com/EXPOIR0405/Tales-of-Balder) | 대화와 저장 슬롯을 갖춘 브라우저 텍스트 RPG. HTML, CSS, JavaScript | **팬 프로젝트** · 전투·퀘스트는 미구현 |

### 상담 코파일럿에서 검증한 것

정책 문서 검색 결과가 없으면 생성 모델을 호출하지 않고, 인용이 없는 답변은 거절하도록 코드로 제어했습니다. 준비 중인 문서를 확정 정책으로 안내하지 않도록 상태도 교정합니다. 저장소의 평가셋은 **가상 서비스의 42문항**이며, README에 잘못된 답변률·상태 정확도·과잉 거절률과 실패 사례를 함께 기록했습니다. 실제 서비스의 고객 성과를 뜻하지 않습니다.

- [데모와 평가 방법](https://github.com/EXPOIR0405/helpdesk-copilot#readme)
- [답변 상태와 근거 검증 코드](https://github.com/EXPOIR0405/helpdesk-copilot/blob/main/src/core/copilot.ts)
- [테스트 코드](https://github.com/EXPOIR0405/helpdesk-copilot/tree/main/test)

## 관심 분야와 기술

- **제품:** 운영 문제 정의, 빠른 프로토타입, 사용자 흐름과 평가 기준 설계
- **AI · 데이터:** 검색 기반 답변, 근거 검증, Python, SQL, Looker Studio
- **개발:** TypeScript, React, Next.js, Node.js, Supabase, Google Apps Script

프로젝트별 구현 범위와 현재 상태는 각 저장소 README에 기록했습니다. 공개 저장소에는 개인 프로젝트와 학습·실험 작업이 함께 있습니다.
