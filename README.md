# YST.grf 자료실입니다.
## 저작권
 CC-BY-NC-SA v3.0 : 비영리조건이며, 스프라이트를 제공한 뒤엔 얼마든지 수정할 수 있습니다.<br>

## 컴퍼일
makefile, [nml0.6.1](https://github.com/OpenTTD/nml) 등의 최신버전을 사용합니다.<br>

## 주의사항
코딩으로 인해 불가피하게 게임내 열차편성이 꼬임이 발생할 수 있습니다.<br>
이로인해 발생한 피해의 문제는 grf에 없기 때문에, 문제없음을 알려드립니다.<br>
또한, 좀더 좋은 방식으로 진행하는 좋은 단계인 만큼 지금보다 더 발전할 수 있도록 응원부탁드립니다.<br>

## 자료공개
공식 : 일자별 최종본이 완성되면 공개합니다. 공개버전은 공개일이 1회로 제한하여 공개합니다.<br>
프리 : 코딩진행하면서 테스트로 만들어진 자료가 있을시, 선공개하는 방식입니다. 릴리즈의 pre-release로 공개됩니다.<br>
공개일 : 정해지지 않습니다. 공개되면 공개되었구나, 하며 넘어가십시오.<br>

##자료제공
YST는 다소 까다로운 템플릿을 보유하고 보다 편한 코딩방식을 택하고 있습니다. 기본적인 템플릿은 순차적으로 만들겠습니다.<br>

##자료활용
그동안 많은 발전을 주신 분들께 진심으로 감사올립니다.<br>
이미 자료를 업로드하여 공개된 자료라면, 얼마든지 수정 수 있으므로, 해당 제작자의 공지는 하지 않겠습니다.<br>

## [YST 2021.11.21](https://github.com/evepoi/YST.grf/releases/tag/2021.11.22)<br>
### 추가
- YPW 1층, 2층, 침대차, 수화물차, 발전차<br>
- MTR IKK SP 1900 전동차<br>
- MTR 현대로템 R형 전동차<br>
- MTR CRRC 창춘 전동차<br>
- MTR AC Cammall 전동차<br>
- 매개변수 : 홍콩형 열차 사용여부<br>
- 객차/화차에 열차구성정보 표시<br>
- 매개변수 : 일본형 열차 사용여부<br>
- 매개변수 : 중국형 열차 사용여부<br>
- 매개변수 : 유럽형 열차 사용여부<br>
- 열차 : AGV-Cool (3002)<br>
- CR600 금색도색 추가<br>
<br>
### 변경
- YN열차이름->TAE로 변경<br>
- 준고속열차 속도증속 251->260km/h<br>
- BB15048, GT26CW, NJ2 끼리 중련구성 불가설정.<br>
- 열차별 숫자 ID 적용.<br>
- 1층공통객차 (2001), 2층 공통객차 (2002) 숫자별 ID 적용.<br>
- makefile 코딩으로 ***.tar 파일생성완료 / 이제 이 파일로 공개합니다.<br>
- 승객차량 Passinger->Passenger 오타 수정.<br>
- 코딩방식 Makefile 변경 (코딩방식으로 변경으로 기존 편성된 차량의 편성이 변경될 수 있습니다.<br>
- 하나의 YST.pnml 세밀 분리 작업완료<br>
- CR600 빨강도색 그래픽 디테일 업.<br>
- CR600+CR600 끼리 중련구성가능.<br>
- 이름변경 공통객차->1층공통객차<br>
- 이름변경 Metro, HMX, NKX 2층 ->2층 공통객차<br>
- 이제 2층형 차량은 2층 공통객차로 구성해야함. 예) KTX-N, TGV Duplex, TGV Old Duplex, 2층 객차 별도구성시 적용.<br>
- TGV 2층형 차량과, 1층형 차량은 코드의 구성불가로 인해 중련구성은 불가능합니다.<br>
<br>
### 제거
- AGV-Cool열차 가상열차로 분리되면서 기존 AGV 도색에서 제거됨.<br>
<br>
### 주의사항
대부분의 TTD 코딩은 Makefile의 최신방식으로 진행됩니다. 물론, 분리설정을 위한 목적이 더 큽니다.<br>
그동안, 편성열차의 꼬임이 발생한 이유는 열차 고유의 숫자 ID가 없었기 때문에 발생한 일이였습니다.<br>
이제, 객차/화차는 2000번대, 열차는 3000번대, 지하철은 4000번대를 사용하면서 편성한 열차가 바뀌는 일은 없을겁니다.<br>
한국열차세트는 5000번대를 사용하고 있기에 확실하게 분리하였습니다.<br>
<br>
다만, 다른 열차세트를 사용할 경우 해당열차가 코드번호와 겹치면서 해당열차의 사용이 충둘로 안될 수 있습니다.<br>
YST의 grf목록이 항상 상위로 설정해두어야 이같은 충돌을 피할 수 있습니다.<br>
