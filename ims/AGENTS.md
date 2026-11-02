# OpenFrame HiDB 추가 지침

## 적용 범위
`$SOURCE_BASE/ims/**`에 적용한다. 환경·Git·증거·보고와 여러 제품의 지침 적용은 루트 `AGENTS.md`를 따른다.

## 담당 기능과 매뉴얼
HiDB는 IBM IMS DB에 대응한다.

- 매뉴얼: `{{manual_base}}` 위키 → OpenFrame HiDB → 대상 제품 버전 → 안내서·장. 조회·편집·저장은 [common-manual-wiki](../.agents/skills/common-manual-wiki/SKILL.md), 본문 작성·수정 기준과 기능 노트는 [common-manual-authoring](../.agents/skills/common-manual-authoring/SKILL.md)를 적용한다.

## 변경과 검증
- Jira의 메시지·매핑·연동·오류 정보는 현재 처리 순서, 실제 인터페이스와 로그에서 검증한다.
- 입력/출력 포맷, 메시지·응답·에러 코드·필드 순서, 매핑·연동 설정을 바꾸면 연동 대상과의 호환성을 확인한다.
- 관련 모듈 테스트와 실제 HiDB 동작 또는 연동 시나리오를 검증한다.
