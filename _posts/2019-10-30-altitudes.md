---
layout: post
title: "비행 중 준수하여야 할 고도들 - Altitudes needed to comply with"
date: 2019-10-30 15:21:00
categories: General Informations
---
#비행 중 중 준수하여야 할 고도들 - Altitudes needed to comply with
###FAA와 ICAO, 그리고 대한민국 - FAA, ICAO and Korea Ministry of Land, Infrastructure and Transport
* 한글 버전

비행 중 준수하여야 할 사항들은 아주 많다. 
그중에서도 가장 중요한 것은 ATC의 지시다. 
그러나 그에 못지 않게 규정 고도 역시 중요하다.
IFR 환경에서는 비행 중 단계에서 적절한 장애물 회피와 항법 및 레이더 신호 송수신을 위해, 
VFR 환경에서는 비행 계획 단계에서 최저 장애물 회피 고도의 결정을 위해서 사전 결정된 항공도 상 고도를 참고한다.
(이 게시글에서 비행 규정이나 자세한 비행 방법은 묘사하지 않는다.)

\
참고한 자료는 FAA : Aeronautical Information Manual, FAA 공식 Chart User's Guide(https://www.faa.gov/air_traffic/flight_info/aeronav/digital_products/aero_guide/), 
14 CFR Part 95, ICAO : Official Documents(Doc 8697, Aeronautical Chart Manual), Korea : Aeronautical Information Manual 입니다.

##FAA 기준
####Sectional Chart & Terminal Area Chart에 도식되는 고도
1. MEF(Minimum Elevation Figure)\
해당 고도가 명시되어 있는 사각 격자 안의 지형물 중 가장 높은 것의 고도이다. 
구체적인 수치가 아닌 100ft 단위로 명시되어 있으며, 5^1 = 5,100ft, 6^8=6,800ft, 13^5=13,500ft과 같이 해석된다.
이 고도 이상에서 비행한다면, 장애물 회피를 보장받는다.
\
이 수치는 다음과 같은 과정을 통해 결정된다.
(가장 높은 장애물의 평균해수면높이 + 발생 가능한 수직 오차 + 장애물 허용 고도)의 100ft 단위 올림 
\
ex) 13110(가장 높은 장애물의 평균 해수면 높이) + 100(발생 가능한 수직 오차) + 200(장애물 허용 고도) = 13410ft, 이를 100ft 단위로 올림한 13,500ft가 MEF가 되며, 차트에는 19^6(그림 참조)과 같이 표시된다.
![MEF](./img/vfr_MEF.jpg)


####IFR Low, High Enroute Chart & Area Chart에 도식되는 고도 
1. MEA(Minimum Enroute Altitude)\
Radio Fixes 사이에서 항법 신호의 원할한 수신과 장애물 회피를 보장하는 최저 고도이다. 전환 구역에서는 최소 300ft, 관제 구역에서는 최소 500ft의 Buffer를 가지도록 설계된다. 장애물, 항법 시설 성능, 통신 요구 사항을 고려하여 결정한다.
\
GNSS(Global Navigation Satelite System) MEA는 파란색과 접미사 "G"로 표시된다.
2. MRA(Minimum Reception Altitude)\
항로와 Fix를 결정하는 항법 시설의 신호 수신을 보장하는 최저 고도이다. 만약 MEA보다 높은 값을 가지게 된다면, MRA 이상에서만 교차점이 정의된다.
3. MAA(Maximum Authorized Altitude)\
공역과 항로를 결정하는 데에 사용될 수 있는 최대 고도이다. 이 고도 이하에서 항법에 이용되는 적절한 신호의 수신이 보장된다.
4. MOCA(Minimum Obstacle Clearance Altitude)\
장애물 회피와 "VOR" 22NM 반경 내에서 신호 수신을 보장하는 고도이다. 해당 지역의 장애물에 ROC(Required Obstacle Clearance)를 고려하여 결정되거나(1차 지역의 장애물 평가), TERPS 항공도를 이용하여 결정한다.(2차 지역의 장애물 평가)
100ft 단위로 표시되지만, MEF와 다르게 이미 장애물 회피에 대한 평가가 이루어진 고도이기 때문에 반올림한다.
5. MTA(Minimum Turning Altitude)\
항로상 지점에서 선회 시 장애물 회피를 보장하는 최저 고도이다. 단, 조종사가 항로를 이탈할 것을 예상하여 해당 지점 이전에 선회할 때에만 보장된다.
6. MCA(Minimum Crossing Altitude)\
해당 Fix를 통과해야 하는 최저 고도이다. MEA가 낮은 고도에서 높은 고도로 바뀌는 경우 설정되며, 이 고도 이하로 Fix를 통과하지 않으면 장애물 회피가 보장되지 않는다.

####MVA, MIA Chart
1. MVA(Minimum Vectoring Altitude)\
IFR 장애물 회피 기준을 만족하는 최저 고도이다. MEA보다 낮을 수 있다. 하지만, 조종사에게 MVA 정보는 항공도 형태로 제공되지 않는다.
2. MIA(Minimum IFR Altitude)\
IFR 항공도에 도식되어 있는 고도를 통해 결정된다. 만약 도식화된 자료가 없다면 비행 경로 좌우측 4NM 범위 내에서 비산악지형의 경우 1,000ft, 산악지형의 경우 2,000ft만큼 자체적으로 회피하여 비행하여야 한다.

####TPP IAP Chart에 도식되는 고도
1. Restrictive Altitudes\
항공로를 따라 설정되는 고도들이다. 아래 표와 같은 고도들이 설정된다.

| 종류 | 설명 | 예시 |
|---|:---:|---:|
|추천되는 고도|별도의 선 없이 표시되는 고도|![REC_ALT](./img/tpp-altitudes-recommended.jpg)|
|최저 고도|고도 아래에 실선|![MIN_ALT](./img/tpp-altitudes-minimum.jpg)|
|최대 고도|고도 위에 실선|![MIN_ALT](./img/tpp-altitudes-maximum.jpg)|
|의무 고도|고도 위, 아래에 실선|![MIN_ALT](./img/tpp-altitudes-manditory.jpg)|
|의무 고도 범위|다수의 고도 위, 아래에 실선|![MIN_ALT](./img/tpp-altitudes-manditory-block.jpg)|
2. MSA(Minimum Safe Altitude)\
특정 Fix 혹은 항법 시설을 중심으로 설정되는 비상 상황에서 이용되는 고도이다. 
반경 25NM 내의 장애물을 평가하며, 1,000ft 이상의 고도로 장애물을 회피하는 것이 보장된다.
상황에서 따라 30NM까지 범위가 확장될 수 있다.
하지만, 항법 신호의 수신은 보장되지 않는다.
유사한 형태로 TAA가 설정된 구역의 항공도에 최저 고도가 표시된다.

##ICAO 기준



--------------------
* 영문 버전\
There are many things to comply while flying. Pilots should mainly comply with ATC instructions and restrictions. But, I think altitude restrictions publicated on official charts are important too. 
Under IFR conditions, these are important to avoid ground obstacles as well as to receive appropriate radio signals, and under VFR conditions, altitude restrictions must be considered while planning the entire flight.
(In this article, I will not illustrate detailed flight maneuvers related to altitude restrictions and regulations) Reference publications I used in this article are these. 
FAA : FAA : Aeronautical Information Manual, FAA Official Chart User's Guide(https://www.faa.gov/air_traffic/flight_info/aeronav/digital_products/aero_guide/), 
14 CFR Part 95, ICAO : Official Documents(Doc 8697, Aeronautical Chart Manual), Korea : Aeronautical Information Manual

##FAA standards
####Altitudes charted on Sectional & Terminal Area Chart
1. MEF(Maximum Elevation Figure)

