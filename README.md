# 제8회 BUSAN ICT융합 해카톤대회
## Team : 3.141592653589793238462643383279502884197
## Hey Pi! Help Us

Application Link : https://www.figma.com/file/3Mln7FVNrHm138A7isIn7w/Untitled?type=design&node-id=0%3A1&mode=design&t=DNRriy4Maj0EbCgh-1

|Tag Name|Description|
|---|---|
|Feat| 새로운 기능을 추가|
|Fix| 버그 수정|
|Design| CSS 등 사용자 UI 디자인 변경|
|!BREAKING CHANGE| 커다란 API 변경의 경우|
|!HOTFIX| 급하게 치명적인 버그를 고쳐야하는 경우|
|Style| 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우|
|Refactor| 프로덕션 코드 리팩토링|
|Comment| 필요한 주석 추가 및 변경|
|Docs| 문서 수정|
|Test| 테스트 코드, 리펙토링 테스트 코드 추가, Production Code(실제로 사용하는 코드) 변경 없음|
|Chore| 빌드 업무 수정, 패키지 매니저 수정, 패키지 관리자 구성 등 업데이트, Production Code 변경 없음|
|Rename| 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우|
|Remove| 파일을 삭제하는 작업만 수행한 경우|

### [ 멘토 1 ]
* 창의성은 좋은 편
* 기존에 시도하고 있었는데 시도 못하고 있던 부분을 찾아내야 한다
* 친구 사진을 올릴 수 있는 기능
* 친구 사진을 어떻게 저장할 것인가
* 모든 기능을 다 넣는 것은 완성도 측에서 불리 할 수 있다
* 작은거라도 시도하지 않았던거 하는게 좋을 듯
* 횡단보도 인식은 조금 어려우니 사람 얼굴 인식을 현실에 가깝게
* 녹내장 환자 수, 85세 이상 노인, 시각 장애인을 타겟으로 잡아라(시장성)
* 실현가능성은 보완해야 한다(우리가 충분히 할 수 있다는걸 알려줘야 함, 수상 실적 등)
* 실 생활에서 사용 할 수 있는 모습
* AI 비전 인식(기술)
* 누가 어떤 역할을 했는가(기술 스택)
* 완성도(물체인식, 사람인식으로 했을 때 좋을거 같고 횡단보도는 안되면 빠르게 버릴 것)

### [ 멘토 2 ]
* 시각 장애인을 도와주는 가이드 좋은거 같다
* 여러가지 케이스에 대한 설명을 해주면 좋을 것 같다
* 상황을 조금 더 중요한 상황을 기준으로 하라
* 신호등이 깜빡이는걸 글로 표현 할 수 없으니 그런 단계가 필요 할 거 같다. (상황 설명을 위한 방법이 필요 할 것 같다.)
* 각 상황에 따른 데이터가 필요하다
* 구체적인 상황을 만들어서 테스트 케이스를 찍어라
* 이런거 저런거 다 하면 질문이 많을 수도 있다
* 상황을 몇가지 설정하는게 중요하다
* 앞으로 이렇게 할것이다. 이런 식으로 나아가라


앱이 방향성이 바뀔 필요는 조금 있어 보인다, 보호자 용 앱이 있는게 가치가 있을거 같다, 이어폰(골전도 이어폰)
수익 모델 같은거 발표하면 좋다, 보호자들끼리의 커뮤니티 구축, 커뮤니티가 어느 정도 있는가(발표 정보),
앱에 대한 방향성을 확실하게, 문제 제시 -> 솔루션 제시 -> 기대 효과 -> 확장 방향성(기능 추가 등),
객관적인 정보 모으는거 중요하다

### [ 대본 추가 할 것 ]
* [ 횡단보도 ]
> 초록불 && 차 없음 = 건널 수 있다.   
> 초록불 && 차 있음 = 못건넌다.   
> 빨간불 && 차 없음 = 못건넌다.   
> 빨간불 && 차 있음 = 못건넌다.   
> 깜빡임 && 차 없음 = 못건넌다.   
> 깜빡임 && 차 있음 = 못건넌다.   