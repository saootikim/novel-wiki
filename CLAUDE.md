# 소설 작업 폴더

- 작업 전에 `novel-project.md`(작품 규칙)를 읽는다.
- 어떤 요청이든 답하기 전에 `skill-autopilot` 스킬의 표로 맞는 스킬을 골라 Skill 도구로 불러온다 (스킬 총괄 길잡이). 도구 사용법 정리는 `도구_사용법_총정리.md`.
- 소설 관련 요청이면 답하거나 작업하기 전에 맞는 스킬을 Skill 도구로 먼저 불러온다. 여러 개가 맞으면 모두 부른다.
  - 평가·점수 (독자 / 처음 보는 사람 / 전문가) → `novel-review`
  - 검토·교정·퇴고 → `novel-editor`
  - 대사·말투 → `novel-character-voice`
  - 플롯·다음 화 계획·아웃라인 → `novel-plot`
  - 설정·위키·연표·복선 → `novel-worldbuilding`
  - 초안 쓰기·문체·묘사 → `novel-genre-style`
  - 사용량 절약·코드 수정·여러 파일 훑기 → `token-saver` (ponytail·graphify·headroom)
  - 화면 확인·디자인·스킬 찾기·서비스 연결·긴 작업 이어가기 → `tool-router` (상황에 맞는 도구 스킬을 골라 준다)
- 인물 말투 기준은 `character-voices.md`에 있다.
- 원고 검사는 /novel-check, 노션→로컬 동기화는 /novel-sync N화. 원고 수정 뒤에는 훅이 검사 결과를 알려 준다.
