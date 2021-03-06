# Functional-JS-Study [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fpikpokjeon%2FFunctional-JS-Study&count_bg=%23FFAD0F&title_bg=%23555555&icon=&icon_color=%23984040&title=%EB%B0%A9%EB%AC%B8%EC%9E%90&edge_flat=true)](https://hits.seeyoufarm.com)
<small> Functional Javascript Study inspired by Haskell </small>
### 함수형 자바스크립트 스터디
> <strong>함수형 패러다임의 철학을 자바스크립트에 녹여 그 원리를 이해</strong> 하기위해 공부합니다. <br /> 외부 자바스크립트 함수형 라이브러리를 답습하지만, 결과물은 나만의 것이 되어야 합니다.

#### Study members
|  팀원 | 아이디 | 참여날짜 |
| -------- | -------- | -------- | 
|전예진 |  [pikpokjeon](https://github.com/pikpokjeon)|  Jun, 1|
| 이연지|  [yzzeee](https://github.com/yzzeee)| Jun, 1|
참여하실 분은 pikpokjeon@gmail.con 으로 연락주세요!
---

| 토픽 | 규칙 | 레퍼런스 |
| -------- | -------- | -------- |
|1. 스터디 방법  |- 각 토픽에 따른 설명과, 최소 2개의 함수를 작성합니다. <br /> - 다음 토픽 시작 일정 까지 각 대분류 토픽의 폴더에 마크다운으로 작성한 결과물을 제출합니다.|```파일명: [토픽이름]---[이름] ```<br /> ``` 위치: /대분류/중분류/파일명.md``` <br />토픽 : 고계함수란? <br /> 설명: ...  <br /> 함수: 1. ... 2. ...  |
|2. 토픽 설명 | - 비교 가능한 주제가 있다면 어떤 차이점이 있는지 서술합니다<br /> - 이해를 돕기위한 코드조각을 첨부하거나 최대한 어려운 용어도 쉽게 풀어 설명 하도록 노력합니다 | 함수가 일급 시민이 아닌 언어는 어떻게 해결하는가. (일급시민이란...)|
|3. 회의 방법  |- 매주 한번 온라인 미팅을 통해 각자 준비한 코드를 화면공유를 통해 리뷰하는 시간을 갖습니다.  <br />- 유닛 테스트 툴을 사용하셔도 좋습니다. 함수가 작동하는 것을 보여주세요. |플랫폼: gather.town <br /> 방식: 화면공유로 정리한 내용을 발표하고, JS 런타임 환경에서 함수가 작동하는 것을 시연합니다.    <br />  |
| 4. 마지막 단계 | - 스터디의 마지막 토픽은 순수 자바스크립트 만으로 함수형 패러다임을 적용한 미니 토이프로젝트를 ~ 2주간 진행합니다.<br /> - 배포는 Github-Pages를 사용합니다. | TODO List, 테트리스게임...|
---

## List to study
- [ ] 시작 날짜
- [x] 완료 시 체크
 ### [ ] 1. 함수형 프로그래밍

* 정의 
* 목적
 - [ ] 6월 26일

### [ ] 2. 절차지향과 함수형 프로그래밍의 차이 ?
* 평가란?
* 불변성이란 ?
- [ ] 6월 26일
* 일급(함수)이란 ? 
* 순수 함수란 ?
- [ ] 6월 
### [ ] 3. 고차(고계)함수란?
* 함수를 인자로 받아 실행하는 함수
- [ ] 6월
* 함수를 리턴하는 함수
 - [ ] 6월 
* 함수를 대신 실행하는 함수를 리턴하는 함수
- [ ] 6월 
### [ ] 4. 콜백 함수와 보조 함수
* 콜백이란?
- [ ] 6월 
* 콜백 함수라 잘못 불리는 보조 함수
  - iteratee
 - [ ] 7월
  - predicate
  - [ ] 7월 
  - mapper
   - [ ] 7월 
- 함수 조립하기
  - 한 번만 실행하는 함수
    - once
    - [ ] 7월 
  
  - 다시 물어보지 않는 함수
    - skip
    - [ ] 7월 
    
  

###  [ ] 5. currying 과 partial
- currying 이란?
- [ ] 7월 
- partial 이란?
- [ ] 7월 
###  [ ] 6. 지연평가
 - [ ] 7월 
### [ ] 7. 함수형 프로그램이 에러를 던지지 않는 이유
- [ ] 7월 
### [ ] 8. 모나드
* 함수자란?
* 모나드

### [ ] 함수를 직접 만들며 뼈대 익히기
    - filter 
    - map
    - find
    - some
    - every
    - compose
    - pipeline
    - identity
    - get
    - each
    - reduce
    - group_by
    - go
    - reject
    - pluck
    - curry
    - curryr
    - range
    - partial
    - compose

### [ ] 지연적인 함수를 직접 만들며 익히기 
    -  L.filter
    -  L.map
    -  L.take
    -  L.takeUtil

###  [ ]조합기를 직접 만들기
    - 항등(identity)
    - 탭(tab)
    - 선택(alternation)

---


#### [ ] Study References
- 함수형 자바스크립트 프로그래밍 (Book)
- tp-js
- lodash
- ramda
- fxjs(https://github.com/marpple/FxJS)
- 
### Commit Convention
```
      [ keyword ] : 커밋 내용 (파일이름)
      keywords : 
                  docs : 문서화,
                  style : 스타일 관련,
                  build : 빌드와 배포,
                  fix: 에러 수정,
                  feature: 기능 추가,
                  refactor: 코드 개선
```
