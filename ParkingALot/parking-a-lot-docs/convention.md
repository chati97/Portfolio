# 컨벤션

## 커밋 제목 규칙

- Script는 겹치지 않도록
- Merge는 다른 사람에게 요청할 것(본인이 머지하지 말것)
- `이슈번호`[`분류`]`커밋 제목`
    - ex) S09P21C102-01[Feat]제목제목
- 분류
    - **대소문자를 그대로 따를 것**.
    - Feat: 새로운 기능을 도입했을 때
    - Mod: 이미 있는 기능을 개선할 때 또는 코드 리팩토링 시
    - Fix: 이미 있는 기능의 오류를 수정할 때
    - Docs: README 같은 문서만 수정했을 경우 사용
- 아래에 상세 내용을 적을 수 있음.

# 유니티 협업

- 버전은 “2022.3.7.f1”으로 통일할 것
- Scene은 최대 1명만 건드리기 → conflict 방지
    - 브랜치를 새로 생성할 때, 작업할 Scene을 복사한 후 그 Scene에서만 작업
    - 브랜치를 병합할 때, 머지하는 사람이 두 Scene을 비교하고 병합
- 각자의 component 및 script는 로컬 프로젝트로
- PUN → 기본적으로 1인이 담당
- 특정 파일을 커밋할 때 .meta 파일이 있다면 반드시 함께 커밋

# 코딩 컨벤션

- 영역 지정 후, ctrl + K + F로 정리된 컨벤션을 활용
    - 전체 지정: ctrl + A
- 변수 명은 camelCase 활용

# 브랜치 이름 컨벤션

- master
- develop
- feat/`오브젝트 이름`/`세부사항`
- hotfix/`오브젝트 이름`/`세부사항`
- 두 단어 이상으로 구성된 경우 snake_case 사용(밑줄로 구분)
- Plastic SCM에선 master, master/develop, [feat], [hotfix] 등을 사용

# 유니티 디렉토리 구조

[[Unity] 유니티 프로젝트를 구성하기 위한 방법](https://velog.io/@jaehyeoksong0/unity-organizing-your-project)

- 폴더 구조 예시 1 사용