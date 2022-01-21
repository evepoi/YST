# OpenTTD YST set 자료실입니다.
## 저작권
 CC-BY-NC-SA v3.0 : 비영리조건이며, 스프라이트를 제공한 뒤엔 얼마든지 수정할 수 있습니다.<br>

## 컴퍼일
makefile, [nml0.6.1](https://github.com/OpenTTD/nml) 등의 최신버전을 사용합니다.<br>

## 자료활용
그동안 많은 발전을 주신 분들께 진심으로 감사올립니다.<br>
저작권 특성상 자유로운 변경공개이므로, 이미 공개된 자료에 대해선 얼마든지 수정하실 수 있습니다.<br>

## 자료공개
공식 : 일자별 최종본이 완성되면 공개합니다. 공개버전은 공개일이 1회로 제한하여 공개합니다.<br>
프리 : 코딩진행하면서 테스트로 만들어진 자료가 있을시, 선공개하는 방식입니다. 릴리즈의 pre-release로 공개됩니다.<br>
공개일 : 정해지지 않습니다. 공개되면 공개되었구나, 하며 넘어가십시오.<br>

## 자료제공
YST는 다소 까다로운 템플릿을 보유하고 보다 편한 코딩방식을 택하고 있습니다. 기본적인 템플릿은 순차적으로 만들겠습니다.<br>

# YST Set 열차 목록
## 개요
객차/화차는 2000번대, 열차는 3000번대, 지하철은 4000번대를 사용합니다. <br>
타 grf의 고유 ID를 사용시 열차고유 ID충돌로 YST 열차셋이 등장하지 않을 수도 있습니다.<br>
우선순위를 위해 grf목록의 YST를 상위로 올리시면 충돌할 일을 없습니다.<br>

## 최근 추가 열차
<details markdown="1">
<summary>내용보기</summary>
<table>
	<thead>
		<tr>
			<th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
		</tr>
	</thead>
	<tbody>
        	<tr>
			<td rowspan="4">일반열차</td>
		</tr>
		<tr>
			<td rowspan="3">3052</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/ITX_SM2_Red.png" alt="ITX-SM2 Red"></td>
		</tr>
		<tr>
			<td>ITX-SM2 빨강도색</td><td>2020년</td><td>181km/h</td><td>운전차량 160, 객차차량 200</td>
		</tr>
		<!-- // ITX-SM2 빨강-->
		<tr>
			<td rowspan="4">일반열차</td>
		</tr>
		<tr>
			<td rowspan="3">3052</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/ITX_SM2_Green.png" alt="ITX-SM2 Green"></td>
		</tr>
		<tr>
			<td>ITX-SM2 녹색도색</td><td>2020년</td><td>181km/h</td><td>운전차량 160, 객차차량 200</td>
		</tr>
		<!-- // ITX-SM2 녹색-->
		<tr>
			<td rowspan="4">일반열차</td>
		</tr>
		<tr>
			<td rowspan="3">3052</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/ITX_SM2_White.png" alt="ITX-SM2 White"></td>
		</tr>
		<tr>
			<td>ITX-SM2 흰색도색</td><td>2020년</td><td>181km/h</td><td>운전차량 160, 객차차량 200</td>
		</tr>
		<!-- // ITX-SM2 흰색-->
		<tr>
			<td rowspan="4">고속열차</td>
		</tr>
		<tr>
			<td rowspan="3">3053</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/KTX_SC2_Blue.png" alt="KTX SC2 Blue"></td>
		</tr>
		<tr>
			<td>KTX-SC2 파랑도색</td><td>2020년</td><td>362km/h</td><td>객차차량 116</td>
		</tr>
		<!-- // KTX-SC2 파랑-->
		<tr>
			<td rowspan="4">고속열차</td>
		</tr>
		<tr>
			<td rowspan="3">3053</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/KTX_SC2_Green.png" alt="KTX SC2 Green"></td>
		</tr>
		<tr>
			<td>KTX-SC2 녹색도색</td><td>2020년</td><td>362km/h</td><td>객차차량 116</td>
		</tr>
		<!-- // KTX-SC2 녹색-->
		<tr>
			<td rowspan="4">고속열차</td>
		</tr>
		<tr>
			<td rowspan="3">3053</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/KTX_SC2_White.png" alt="KTX SC2 White"></td>
		</tr>
		<tr>
			<td>KTX-SC2 흰색도색</td><td>2020년</td><td>362km/h</td><td>객차차량 116</td>
		</tr>
		<!-- // KTX-SC2 흰색-->
        <tr>
			<td rowspan="4">일반열차</td>
		</tr>
		<tr>
			<td rowspan="3">3054</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/NRT2_Blue.png" alt="NRT2 Blue"></td>
		</tr>
		<tr>
			<td>NRT2 파랑도색</td><td>2020년</td><td>181km/h</td><td>운전차량 160, 객차차량 116</td>
		</tr>
		<!-- // NRT2 파랑-->
        <tr>
			<td rowspan="4">일반열차</td>
		</tr>
		<tr>
			<td rowspan="3">3054</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/NRT2_Green.png" alt="NRT2 Green"></td>
		</tr>
		<tr>
			<td>NRT2 녹색도색</td><td>2020년</td><td>181km/h</td><td>운전차량 160, 객차차량 116</td>
		</tr>
		<!-- // NRT2 녹색-->
        <tr>
			<td rowspan="4">일반열차</td>
		</tr>
		<tr>
			<td rowspan="3">3054</td>
		</tr>
		<tr>
			<td colspan="4"><img src="docs/img/YST/NRT2_White.png" alt="NRT2 White"></td>
		</tr>
		<tr>
			<td>NRT2 흰색도색</td><td>2020년</td><td>181km/h</td><td>운전차량 160, 객차차량 116</td>
		</tr>
		<!-- // NRT2 흰색-->
</table>
</details>

## 지하철
<details markdown="2">
<summary>내용보기</summary>
<table>
    <thead>
        <tr>
            <th>열차<th>도입</th><th>열차속도</th><th>수송</th>
        </tr>
    </thead>
	<tbody>
		<tr>
			<td>4001</td><td colspan="3">TR AD Tranz CAF A형</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4001.png" alt="4001"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4001-->
		<tr>
			<td>4002</td><td colspan="3">MTR 메트로카멜 교류형 전동차</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4002.png" alt="4002"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4002-->
		<tr>
			<td>4003</td><td colspan="3">MTR 메트로카멜 직류형 전동차</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4003.png" alt="4003"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4003-->
		<tr>
			<td>4004</td><td colspan="3">MTR CNR 창춘 전동차</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4004.png" alt="4004"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4004-->
		<tr>
			<td>4005</td><td colspan="3">MTR CRRC 전동차</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4005.png" alt="4005"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4005-->
		<tr>
			<td>4006</td><td colspan="3">MTR 현대로템 미쓰비시 전동차</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4006.png" alt="4006"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4006-->
		<tr>
			<td>4007</td><td colspan="3">MTR 현대로템 R형 전동차</td>
		</tr>
		<tr>
			<td><img src="docs/img/YST/4007.png" alt="4007"></td><td>1979</td><td>120km/h</td><td>80</td>
		</tr>
		<!-- // 4007-->
	</tbody>
</table>
</details>

## 일반열차
<details markdown="3">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>

## 고속열차
### 260km/h급 
<details markdown="4">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>
	
### 362km/h급 
<details markdown="5">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>
	
### 430km/h급 
<details markdown="6">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>

### 600km/h급 
<details markdown="7">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>

## 기관차
<details markdown="8">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>

## 화물열차
<details markdown="9">
<summary>내용보기</summary>
곧 추가됩니다.
<table>
    <thead>
        <tr>
            <th>구분</th><th>ID</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
        </tr>
    </thead>
	<tbody>
	</tbody>
</table>
</details>