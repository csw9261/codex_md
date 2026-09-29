# Codex AGENTS.md

개인 Codex 전역 지침의 버전 관리를 위한 저장소. [`AGENTS.md`](AGENTS.md)는 `~/.codex/AGENTS.md`의 복사본.

## 주요 내용

- 구현 전 가정과 범위 확인, 단순한 해결책 우선
- 요청 범위에 필요한 부분만 수정하고 검증 가능한 완료 기준 설정
- 확인한 증거에 근거한 진단과 보고
- 한국어 문서·주석 작성 규칙, 저장소 변경 Git 명령의 사전 승인, 에이전트 작업 규모 제한

## 적용

저장소의 지침을 Codex 전역 설정에 적용:

```sh
cp AGENTS.md ~/.codex/AGENTS.md
```

전역 설정을 수정한 뒤 이 저장소의 복사본 갱신:

```sh
cp ~/.codex/AGENTS.md AGENTS.md
```
