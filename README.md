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
</table>
</details>

## 지하철
<details markdown="2">
<summary>내용보기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR.png" alt="MTR"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR -->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR 개조형</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR_remoding.png" alt="MTR remoding"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR 개조형-->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR 디즈니</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR_Disney.png" alt="MTR Disney"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR 디즈니-->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR CNR</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR_CNR.png" alt="MTR CNR"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR CNR-->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR CNR 남부섬</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR_CNRN.png" alt="MTR CNR 남부섬"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR CNR 남부섬-->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR CRRC</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR_CRRC.png" alt="MTR CRRC"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR CRRC-->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">MTR 미쓰비시</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/MTR_H.png" alt="MTR 미쓰비시"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1979년</td><td>120km/h</td><td>운전차량 80, 객차차량 80</td>
                                        </tr>
                                        <!-- // MTR 미쓰비시-->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 100 A도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_100_A.png" alt="YTRO 100 A도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 100 B도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_100_B.png" alt="YTRO 100 B도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 100 C도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_100_C.png" alt="YTRO 100 C도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 100 D도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_100_D.png" alt="YTRO 100 D도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 100 E도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_100_E.png" alt="YTRO 100 E도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <!-- // YTRO 100 -->
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 A도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_A.png" alt="YTRO 200 A도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 B도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_B.png" alt="YTRO 200 B도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 C도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_C.png" alt="YTRO 200 C도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 D도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_D.png" alt="YTRO 200 D도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 E도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_E.png" alt="YTRO 200 E도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 F도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_F.png" alt="YTRO 200 F도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 G도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_G.png" alt="YTRO 200 G도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 H도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_H.png" alt="YTRO 200 H도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 I도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_I.png" alt="YTRO 200 I도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">지하철</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTRO 200 J도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTRO_200_J.png" alt="YTRO 200 J도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>120km/h</td><td>운전차량 80, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <!-- // YTRO 200 -->
                                </table>
</details>

## 일반열차
<details markdown="3">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">일반열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">NKX A도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/NKX_A.png" alt="NKX A도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>150km/h</td><td>운전차량 72, 1층 객차차량 101, 2층 객차차량 202</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">일반열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">NKX B도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/NKX_B.png" alt="NKX B도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>150km/h</td><td>운전차량 72, 1층 객차차량 101, 2층 객차차량 202</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">일반열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">NKX C도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/NKX_C.png" alt="NKX C도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>150km/h</td><td>운전차량 72, 1층 객차차량 101, 2층 객차차량 202</td>
                                        </tr>
                                        <!-- // NKX -->
                                        <tr>
                                            <td rowspan="4">일반열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YN01</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YN01.png" alt="YN01"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>180km/h</td><td>운전차량 58, 객차차량 70</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">일반열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YN01-Yellow</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YN01_Yellow.png" alt="YN01-Yellow"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>180km/h</td><td>운전차량 58, 객차차량 70</td>
                                        </tr>
                                </table>
</details>

## 고속열차
### 260km/h급 
<details markdown="4">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">800계</td>
                                        </tr>
                                           <tr>
                                            <td colspan="3"><img src="img/YST/800.png" alt="신칸센 800계"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1996년</td><td>260km/h</td><td>운전차량 58, 객차차량 80</td>
                                        </tr>
                                        <!-- // 신칸센 800계 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">CRH1</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/CRH1.png" alt="CRH1"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>280km/h</td><td>운전차량 72, 객차차량 101</td>
                                        </tr>
                                        <!-- // CRH1 -->
                                        <tr>
                                            <td rowspan="4">준고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">EMU-250</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/EMU_250.png" alt="EMU-250"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>251km/h</td><td>운전차량 58, 객차차량 70</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">준고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">HMX 빨강도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/HMX_Red.png" alt="HMX-Red"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>251km/h</td><td>운전차량 40, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">준고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">HMX 녹색도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/HMX_Green.png" alt="HMX-Green"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>251km/h</td><td>운전차량 40, 1층 객차차량 80, 2층 객차차량 160</td>
                                        </tr>
                                        <!-- // HMX -->
                                        <tr>
                                            <td rowspan="4">준고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Talgo250-Alvia</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Talgo_250_Alvia.png" alt="Talgo-250 Alvia"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>250km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">준고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Talgo250-Aprosiyob</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Talgo_250_Aprosiyob.png" alt="Talgo-250 Aprosiyob"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>250km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // Talgo250 -->
                                        <tr>
                                            <td rowspan="4">준고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YN02</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YN02.png" alt="YN02"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>251km/h</td><td>운전차량 58, 객차차량 70</td>
                                        </tr>
                                        <!-- // YN -->
                                </table>
	
</details>
	
### 362km/h급 
<details markdown="5">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">500계</td>
                                        </tr>
                                           <tr>
                                            <td colspan="3"><img src="img/YST/500.png" alt="신칸센 500계"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1996년</td><td>330km/h</td><td>운전차량 53, 객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">500계-팥죽</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/500_Patjug.png" alt="신칸센 500계-팥죽"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1996년</td><td>330km/h</td><td>운전차량 53, 객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">500계-산천</td>
                                        </tr>
                                            <tr>
                                            <td colspan="3"><img src="img/YST/500_Sancheon.png" alt="신칸센 500계-산천"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1996년</td><td>330km/h</td><td>운전차량 53, 객차차량 100</td>
                                        </tr>
                                        <!-- // 신칸센 500계 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">AGV</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/AGV.png" alt="AGV"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>330km/h</td><td>운전차량 85, 객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">AVE</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/AVE.png" alt="AVE"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>330km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // AVE -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">AVE Velaro</td>
                                        </tr>
                                           <tr>
                                            <td colspan="3"><img src="img/YST/AVE_Velaro.png" alt="AVE"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2006년</td><td>330km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <!-- // AVE Velaro -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">CRH3</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/CRH3.png" alt="CRH1"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2017년</td><td>330km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <!-- // CRH3 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">CRH380A</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/CRH380A.png" alt="CRH380A"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2017년</td><td>380km/h</td><td>운전차량 46, 객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">CRH380A-Red</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/CRH380A_Red.png" alt="CRH380A_Red"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2017년</td><td>380km/h</td><td>운전차량 46, 객차차량 85</td>
                                        </tr>
                                        <!-- // CRH380A -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">E5</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/E5.png" alt="E5"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2011년</td><td>330km/h</td><td>운전차량 20, 객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">H5</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/H5.png" alt="H5"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2011년</td><td>330km/h</td><td>운전차량 20, 객차차량 100</td>
                                        </tr>
                                        <!-- // E5 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">E6</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/E6.png" alt="E6"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2011년</td><td>330km/h</td><td>운전차량 22, 객차차량 68</td>
                                        </tr>
                                        <!-- // E6 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">E7</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/E7.png" alt="E7"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2014년</td><td>331km/h</td><td>운전차량 50, 객차차량 98</td>
                                        </tr>
                                        <!-- // E7 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">E300 노랑도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/E300_A.png" alt="E300 노랑도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1992년</td><td>331km/h</td><td>객차차량 58</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">E300 파랑도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/E300_B.png" alt="E300 파랑도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1992년</td><td>331km/h</td><td>객차차량 58</td>
                                        </tr>
                                        <!-- // E300 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">E320</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/E320.png" alt="E320"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2014년</td><td>331km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <!-- // E320 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">EMU-300</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/EMU_300.png" alt="EMU-300"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>331km/h</td><td>운전차량 58, 객차차량 70</td>
                                        </tr>
                                        <!-- // EMU -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">ICE3</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/ICE3.png" alt="ICE3"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1997년</td><td>331km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <!-- // ICE3 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">ICE-SP (산천)</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/ICE_Sancheon.png" alt="ICE-산천"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>331km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">ICE-SP (팥죽)</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/ICE_Patjug.png" alt="ICE-팥죽"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>331km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <!-- // ICE-SP -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">KTX-N</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/KTX_N.png" alt="KTX-N"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>331km/h</td><td>객차차량 116</td>
                                        </tr>
                                        <!-- // KTX-N -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">N700</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/N700.png" alt="N700"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2007년</td><td>331km/h</td><td>운전차량 75, 객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">타이완 고속열차</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/N700_Taiwan.png" alt="타이완고속열차"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2007년</td><td>331km/h</td><td>운전차량 75, 객차차량 100</td>
                                        </tr>
                                        <!-- // N700 -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV-Old</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_Old.png" alt="TGV Old"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1978년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // TGV-Old -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Old Pos</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_OLD_POS.png" alt="TGV Old Pos"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1978년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Old Lyair</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_OLD_POS_Lyair.png" alt="TGV Old Pos Lyair"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1978년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Old Thalys</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_OLD_POS_Thalys.png" alt="TGV Old Pos Thalys"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1978년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // TGV Old Pos -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Pos</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_POS.png" alt="TGV Pos"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2006년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Lyair</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_POS_Lyair.png" alt="TGV Lyair"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2006년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Thalys</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_POS_Thalys.png" alt="TGV Thalys"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2006년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // TGV Pos -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Old Duplex</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_OLD_Duplex.png" alt="TGV Old Duplex"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1994년</td><td>250km/h</td><td>객차차량 170</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Old Lyair Duplex</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_OLD_Duplex_Lyair.png" alt="TGV Old Duplex Lyair"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1994년</td><td>250km/h</td><td>객차차량 170</td>
                                        </tr>
                                        <!-- // TGV Old Duplex -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Duplex</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_Duplex.png" alt="TGV Duplex"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1994년</td><td>250km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Lyair Duplex</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_Duplex_Lyair.png" alt="TGV Duplex Lyair"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1994년</td><td>250km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // TGV Duplex -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">TGV Ouigo</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/TGV_Ouigo.png" alt="TGV Ouigo"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2013년</td><td>331km/h</td><td>객차차량 85</td>
                                        </tr>
                                        <!-- // TGV Ouigo -->
                                        <tr>
                                            <td rowspan="4">고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">YTX</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YTX.png" alt="YTX"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>331km/h</td><td>운전차량 30, 객차차량 50</td>
                                        </tr>
                                        <!-- // YTX -->
                                        <tr>
                                            <td rowspan="4">고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">ZEFIRO380</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/ZEFIRO380.png" alt="ZEFIRO380"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2014년</td><td>380km/h</td><td>운전차량 54, 객차차량 90</td>
                                        </tr>
                                    </tbody>
                                    <!-- // ZEFIRO380 -->
                                </table>
	
</details>
	
### 430km/h급 
<details markdown="6">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">500계-Cool</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/500_Cool.png" alt="신칸센 500계-Cool"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>1996년</td><td>430km/h</td><td>운전차량 53, 객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">AGV-Cool</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/AGV_Cool.png" alt="AGV-Cool"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>430km/h</td><td>운전차량 85, 객차차량 85</td>
                                        </tr>
                                        <!-- // AGV -->
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">CRH380A-Cool</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/CRH380A_Cool.png" alt="CRH380A_Cool"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2017년</td><td>430km/h</td><td>운전차량 46, 객차차량 85</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">HEMU-430</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/HEMU.png" alt="HEMU-430"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2007년</td><td>430km/h</td><td>운전차량 60, 객차차량 80</td>
                                        </tr>
                                        <!-- // HEMU-430 -->
                                        <tr>
                                            <td rowspan="4">고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">ZEFIRO380-Cool</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/ZEFIRO380_Cool.png" alt="ZEFIRO380-Cool"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2014년</td><td>430km/h</td><td>운전차량 54, 객차차량 90</td>
                                        </tr>
                                    </tbody>
                                    <!-- // ZEFIRO380 -->
                                </table>
	
</details>

### 600km/h급 
<details markdown="7">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">CR600</td>
                                        </tr>
                                           <tr>
                                            <td colspan="3"><img src="img/YST/CR600.png" alt="CR600"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2012년</td><td>600km/h</td><td>운전차량 45, 객차차량 90</td>
                                        </tr>
                                        <!-- // CR600 -->
                                        <tr>
                                            <td rowspan="5">시운전고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">CRH380A-Test</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/CRH380A_Test.png" alt="CRH380A-Test"></td>
                                        </tr>
                                        <tr>
                                            <td>2017년</td><td>600km/h</td><td>수송량 없음</td>
                                        </tr>
                                        <tr class="tr">
                                            <td colspan="3">시운전차량으로 기관사와 보조 기관사만 탑승한다는 컨셉임. 유지보수 0</td>
                                        </tr>
                                        <!-- // CRH380A-Test -->
                                        <tr>
                                            <td rowspan="5">시운전고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">Dr. Yellow</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Dr_Yellow.png" alt="Dr.Yellow"></td>
                                        </tr>
                                        <tr>
                                            <td>2007년</td><td>600km/h</td><td>수송량 없음</td>
                                        </tr>
                                        <tr class="tr">
                                            <td colspan="3">시운전차량으로 기관사와 보조 기관사만 탑승한다는 컨셉임. 유지보수 0</td>
                                        </tr>
                                        <!-- // Dr. Yellow -->
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Glory 600 A도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Glory_600_A.png" alt="Glory-600 A도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>600km/h</td><td>객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Glory 600 B도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Glory_600_B.png" alt="Glory-600 B도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>600km/h</td><td>객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Glory 600 C도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Glory_600_C.png" alt="Glory-600 C도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>600km/h</td><td>객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Glory 600 D도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Glory_600_D.png" alt="Glory-600 D도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>600km/h</td><td>객차차량 100</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">Glory 600 E도색</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/Glory_600_E.png" alt="Glory-600 E도색"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>600km/h</td><td>객차차량 100</td>
                                        </tr>
                                        <!-- // Glory 600 -->
                                        <tr>
                                            <td rowspan="4">초고속철도</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">VTX</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/VTX.png" alt="VTX"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2020년</td><td>600km/h</td><td>운전차량 40, 객차차량 80</td>
                                        </tr>
                                        <!-- // VTX -->
                                        <tr>
                                            <td rowspan="5">화차형 고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="4">YFX</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/YFX.png" alt="YFX"></td>
                                        </tr>
                                        <tr>
                                            <td>2020년</td><td>600km/h</td><td>운전차량 100, 증결차량 200</td>
                                        </tr>
                                        <tr class="tr">
                                            <td colspan="3">※ 본 차량은 화물열차로 승객외 모든 화물을 운반합니다.</td>
                                        </tr>
                                        <!-- // YFX -->
                                        <tr>
                                            <td rowspan="4">초고속열차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">ZEFIRO380-Black</td>
                                        </tr>
                                        <tr>
                                            <td colspan="3"><img src="img/YST/ZEFIRO380_Black.png" alt="ZEFIRO380-Black"></td>
                                        </tr>
                                        <tr class="tr">
                                            <td>2014년</td><td>600km/h</td><td>운전차량 54, 객차차량 90</td>
                                        </tr>
                                    </tbody>
                                    <!-- // ZEFIRO380 -->
                                </table>
	
</details>

## 기관차
<details markdown="8">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">전기기관차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">BB15048</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/BB15048.png" alt="BB15048"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1971년</td><td>180km/h</td><td>전기기관차로 수송량 없음.</td>
                                        </tr>
                                        <!-- // BB15048 -->
                                        <tr>
                                            <td rowspan="4">디젤기관차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">GT26CW</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/GT26CW.png" alt="GT26CW"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1967년</td><td>180km/h</td><td>디젤기관차로 수송량 없음.</td>
                                        </tr>
                                        <!-- // GT26CW -->
                                        <tr>
                                            <td rowspan="4">디젤기관차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">NJ2</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/NJ2.png" alt="NJ2"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>2006년</td><td>180km/h</td><td>디젤기관차로 수송량 없음.</td>
                                        </tr>
                                        <!-- // NJ2 -->
                                </table>
	
</details>

## 화물열차
<details markdown="9">
<summary>접기/펼치기</summary>
<table class="table2">
                                    <thead>
                                        <tr>
                                            <th>구분</th><th>열차이름</th><th>도입년도</th><th>열차속도</th><th>수송량</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td rowspan="4">화차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">컨테이너화차</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/Flat_1F.png" alt="Flat 1F"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1967년</td><td>기관차 속도 귀속</td><td>50 / FIRS 대응</td>
                                        </tr>
                                        <!-- // 컨테이너 화차 1F -->
                                        <tr>
                                            <td rowspan="4">화차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">컨테이너 탱크화차</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/Flat_Tank.png" alt="Flat Tank"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1967년</td><td>기관차 속도 귀속</td><td>액체화물 100 / FIRS 대응</td>
                                        </tr>
                                        <!-- // 컨테이너 화차 1F -->
                                        <tr>
                                            <td rowspan="4">화차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">컨테이너 미국형</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/Flat_2F.png" alt="Flat 미국형"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1967년</td><td>기관차 속도 귀속</td><td>50 / FIRS 대응</td>
                                        </tr>
                                        <!-- // 컨테이너 화차 2F -->
                                        <tr>
                                            <td rowspan="4">화차</td>
                                        </tr>
                                        <tr>
                                            <td rowspan="3">유조화차</td>
                                        </tr>
                                            <tr>
                                                <td colspan="3"><img src="img/YST/tank.png" alt="Tank"></td>
                                            </tr>
                                        <tr class="tr">
                                            <td>1967년</td><td>기관차 속도귀속</td><td>액체화물 200,000L / FIRS 대응함.</td>
                                        </tr>
                                        <!-- // Tank -->
                                </table>
	
</details>
