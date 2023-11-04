# suwonbus

## 프로젝트 개요
### 경기권과 서울 도심을 연결해주는 수많은 광역버스는 경기도민의 중요한 교통수단 중 하나이다. 
### 많은 사건 사고들을 거치면서 이러한 광역버스는 많은 변화를 겪었는데 특히 작년 11월에 시행했던 입석금지 조치로 인해 버스 이용에 많은 변화가 생겼다는 것을 체감하고 있다.
### 이에, 코로나를 거치면서, 그리고 입석금지 조치가 시행되면서 수원시 내 광역버스 이용 실태에 대해 분석하고 이를 통해 광역버스 예약 어플인 'Miri' 서비스에 가장 시급하게 추가해야할 노선이 무엇인지 발굴하고자 한다.
#### 19년 9월 코로나X, 입석금지 X
#### 22년 9월 코로나O, 입석금지 X
#### 23년 9월 코로나X, 입석금지 O

## 분석 방향
### chapter1. 수원시 광역버스 승차 이용행태 분석
#### ① 날씨에 따른 영향(강수, 태풍, 기온 등) : 3개년 통합 데이터 이용하여 상관관계 분석(승차인원수 total값으로 분석)
#### ② 추석직전/추석기간/직후 영향 분석 : 3개년 통합 데이터 이용하여 상관관계 분석(추석직전/기간/직후 주 vs 추석 일주일전/후 기간 비교)
#### ③ 수원시 구 별 승차인원 분석 (승차인원수 total값으로 분석)
#### ④ 평일 vs 주말 승차 행태 비교 (승차 total값, 시간대별 차이, 승차정류장별 차이)
#### ⑤ 평일 시간대별 승차 분석 
#### ⑥ ⑤에서 도출된 최대 승차 시간대에서 가장 많은 승차가 이루어지는 정류장 분석
### chapter2. 코로나 및 입석금지 조치 시행에 따른 승차 이용행태 분석
#### ⑦ 19-22년-23년 승차 정류장 차이 (지도 맵 시각화) : 큰 변화 없을 가능성이 높음
#### ⑧ 19년 vs 22년 vs 23년 (코로나 이전 / 코로나 / 포스트 코로나) 승차 이용 행태 분석 (total값, 출근시간대, 퇴근시간대, 평일 vs 주말)
#### ⑨ 22년 vs 23년 (입석금지 조치 시행으로 인해) 승차 이용 행태 분석 (total값, 출근시간대, 퇴근시간대, 평일 vs 주말)
    승차 gap이 가장 많이 나는 정류장 (출근시간대 / 퇴근시간대)
#### ⑩ ⑨결과로 인해 ㅇㅇ정류장, xx정류장에서 승차 gap이 가장 많이 나 입석금지 조치 시행으로 인해 가장 큰 변화가 일어났음을 알 수 있다. 
   ---> 그 정류장 중심의 노선으로 Miri앱 예약 노선 우선 배치 필요 (시간 남으면 해당 정류장에서 gap이 가장 큰 버스 노선까지 분석할 수 있으면 좋음)
