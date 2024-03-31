## Commit Convention

### **Basic Struture**

```
[type] : subject

body(optional)

footer

```

### **Type**

- **FEAT : 새로운 기능**
- **FIX : 버그 수정**
- **UI : UI 변경**
- **REFACTOR : 리팩토링**
- **DOCS** : 문서 수정
- **TEST** : 테스트 코드 추가/테스트 리팩토링
- **CHORE** : updating build tasks, package manager 설정

### **Subject**

- Subject는 50글자를 넘어가면 안된다
- 첫 시작은 대문자로 해야한다
- 마지막에 마침표(.)를 찍으면 안된다
- 어떤 변경점이 있는지 설명한다
- 명령조를 사용한다
- 한글로, 영어가 제일 앞에 나올 때는 대문자, 동사로 끝내기

### **Body**

- 부연 설명이나 커밋의 이유를 설명할 때만 사용
- Not How, Explauin What and Why
- 윗 부분과 1줄의 공백 필요
- 각 라인은 72자 초과 불가

### **Footer**

- Issue Tracker IDs를 적을 때 사용
- issue track : branch prefix/#{issue_number} 형태로 기입

## Issues Convention

- 이슈 이름
    - `[PREFIX] <Description>` 의 양식을 준수, Prefix는 대문자 사용
    - PREFIX = `UI`, `FEAT`, `CHORE`, `REFACTOR`
    - `UI`
        
        UI에 대한 수정사항
        
    - FEAT
        - 기능을 추가, 수정
    - CHORE
        - 프로젝트 구성 파일, 프로젝트 생성
    - REFACTOR
        - 리팩토링 약자, 리팩토링 → 코드 리뷰 반영, 코드를 수정하거나, 불필요한 코드를 제거하는 작업. 필요에 따라서 함수 호출 위치를 수정한다던가
- 이슈 내용
    - 이슈 템플릿 사용
    - 이슈 생성 시 Assignee, Label, Project, Milestone 사용

## Branch Convention

- 이슈를 기반으로 작성
- 브랜치 이름
    - prefix/#이슈번호 - 설명

### **Git-Flow 사용**

- Master - 고객에게 바로 배포
- Develop - 개발 단계
- Feature - 기능 추가
- Hotfix - 버그 핫픽스

## PR Convention

- PR 이름
    - [이슈 type] 설명
- PR 내용
    - PR 템플릿 사용
    - close #이슈번호
    - 이슈 생성 시 Assignee, Label, Project 사용
