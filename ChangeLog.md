# Git 브랜치전략 및 커밋 컨벤션 설정

## 1. 브랜치 전략 

 <img src="https://github.com/9-1379/T3-R0-Document/assets/148875683/de1e7ca6-a81f-4b90-89ef-f2827c426db7" width="700px">

### - dev <br/>
: 각자 feature 브랜치 생성 - 브랜치 이름은 wbs 번호로 네이밍 할 것.<br/>
<br/>

### - feature <br/>
: 풀리퀘 생성하여 커밋할 것. <br/>
: merge 필요할 경우 TL 에게 최종 컨펌 후 가능.<br/>
<br/>

### - release <br/>
: feature브랜치가 모두 dev에 병합 된 후 생성.<br/>
: 배포를 위한 최종 버그 수정  <br/>
: QA / Test 진행<br/>
: 모든 과정 완료 후 main 브랜치와 병합<br/>
: dev 브랜치와 병합<br/>
<br/>

### - main <br/>
: 버전 태그 생성.<br/>
: 배포 !<br/>


## 2. 커밋 컨벤션 정의

| 태그 종류 |설명|
-- | --
Add | 기능 추가
Fix | 버그 고친 경우
Docs | 문서 수정 - 문서 파일에만 / 코드 x
Refactor | 코드 리펙토링
Test | 테스트 코드
Remove | 코드 삭제시
Modify | 코드 수정시

예시) <br/>
[Add] 코드 기능 추가 <br/>
[Docs] 리드미 파일 수정 
