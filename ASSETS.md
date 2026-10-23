# ASSETS — Day Zero 발표 덱

## 컨셉
캐릭터: 성별·나이를 특정하지 않는 단순한 사람 실루엣형 인물. 실존 인물·사진 느낌 금지. AI 동료는 같은 스타일의 인물 3명으로, 성향을 과장하지 않는 중립 표정.
톤: 플랫 에디토리얼 일러스트, 얇은 선 + 면 채색, 배경은 따뜻한 미색(#FAF9F5) 단색, 잉크(#141413)·회색(#6B6A64)·연회색(#DEDCD3) 위주에 클레이(#D97757) 포인트 한 곳.
금지: 이미지 안 글자·숫자·로고, 사실적 명암, 복잡한 배경, 보라·파랑 그라데이션, 로봇·반짝이 아이콘, 네온.

## 자산
| 파일 | 쓰는 장 | 무엇을 보여주는가 | 프롬프트 요지 | 출처 |
|---|---|---|---|---|
| assets/cover-hook.png | 1 표지 | 지원자 한 명이 노트북 앞에서 화면 속 AI 동료 3명과 토론하는 장면 | 노트북 화면에 인물 아바타 3개와 말풍선(글자 없음), 앞에 앉은 지원자 뒷모습, 클레이 포인트는 지원자 말풍선 | codex 생성 |
| assets/problem-mask.png | 2 문제 | 인성검사 답안지 앞에서 웃는 가면을 얼굴에 대고 있는 지원자 (꾸민 응답의 은유) | 책상 위 체크형 답안지(글자 없음), 손에 든 웃는 가면, 클레이 포인트는 가면 | codex 생성 |
| assets/debate-crop.png | 3 해결책 | 실제 토론 화면 일부 | e2e 기록 캡처 잘라 냄 | tests/e2e/records/stages/problem/02-수용 카드.png |
| assets/flow-*.png | 5 서비스 흐름 | 단계별 실제 화면 일부 | e2e·제품 가이드 캡처 잘라 냄 | tests/e2e/records/stages, docs/share/product-guide/media |
| assets/report-crop.jpg | 7 담당자 경험 | 실제 LLM 리포트의 세부 행동 하나(수준·확신도·판단 이유·설계된 장면) | 로컬 스택 관리자 리포트 화면 캡처 | 가상 지원자 실제 LLM 세션(2026-10-23) |
| assets/flow-4-report.jpg | 5 서비스 흐름 | 실제 LLM 리포트 요소 요약 | 같은 세션 캡처 | 같은 세션 |
| assets/demo-poster.png | 12 시연 | 영상 자리 대표 화면 | 기존 캡처 복사 | docs/share/report-assets/real-debate.png |
| assets/diagram-*.svg | 8~11 설계 | 아키텍처·에이전트·MCP·하네스 | 덱 크기(1172×400, 글자 16px 이상)로 새로 그린 SVG. 다시 그릴 때는 `python3 tools/diagrams.py assets` 를 고쳐 재생성 | docs/architecture 기준 |
