# oh-my-opencode-slim 오픈소스 기여

> OpenCode용 멀티 에이전트 도구에서 사용할 수 없게 된 Gemini 모델을
> 3.1 Pro로 갱신하고, 관련 코드·테스트·문서를 함께 정리했습니다.

[Upstream Repository](https://github.com/alvinunreal/oh-my-opencode-slim)
· [Pull Request #143](https://github.com/alvinunreal/oh-my-opencode-slim/pull/143)
· [변경 코드](https://github.com/alvinunreal/oh-my-opencode-slim/pull/143/files)

---

## 기여 정보

- 기여 시점: 2026.02
- 기술: TypeScript, Bun
- 결과: upstream `master` 브랜치 병합

## 기여 배경

기존에 사용하던 Gemini 3 Pro 모델이 3.1 Pro로 업데이트되면서 이전 모델 ID로는
서비스를 정상적으로 사용할 수 없었습니다.

새 모델을 사용하려면 Provider mapping과 설정 생성 코드를 변경해야 했으며, 모델 ID가
설치 과정, 테스트와 사용자 문서에도 사용되고 있어 관련 참조를 함께 갱신해야 했습니다.

## 기여 내용

저장소 전체에서 기존 Gemini 3 Pro 모델이 사용되는 위치를 확인하고 다음 내용을 하나의
PR에서 수정했습니다.

- Provider mapping과 설정 생성 코드에 Gemini 3.1 Pro 모델 정보 반영
- 설치 과정에서 사용하는 모델 ID와 표시 이름 변경
- 새 모델 ID가 반영된 선택 결과에 맞춰 테스트 기대값과 문서 수정

모델 선택 알고리즘은 변경하지 않고, 기존 로직이 새 모델 ID를 사용하도록 변경 범위를
제한했습니다.

## 검증과 결과

프로젝트에서 요구하는 테스트, TypeScript 타입 검사와 Biome 정적 검사를 통과한 뒤
기여 형식에 맞춰 PR을 제출했습니다.

[PR #143](https://github.com/alvinunreal/oh-my-opencode-slim/pull/143)은 upstream
`master` 브랜치에 병합되었습니다.

## 기여를 통해 배운 점

외부 모델의 버전 변경은 이름 하나를 바꾸는 작업으로 끝나지 않고 Provider 설정,
설치 과정, 테스트와 문서까지 영향을 줄 수 있다는 점을 경험했습니다.

또한 외부 프로젝트에 기여할 때는 문제를 해결하는 것뿐 아니라 기존 로직을 유지하고,
프로젝트의 검증 절차와 기여 규칙을 만족시키는 과정도 중요하다는 것을 배웠습니다.

[← 포트폴리오 인덱스로 돌아가기](../README.md)
