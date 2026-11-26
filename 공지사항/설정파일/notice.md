다양한 케이스에 대한 settings.json 파일 배포합니다. (첨부)

첨부 파일을 참고해서, 주행 Simulator를 실행하기 바랍니다.

settings.json 수정하기

path : C:\user{사용자계정명, 예 -> SDS, 영문 O, 한글 X)\Documents\AirSim

File : settings.json

json
{
"SettingsVersion": 1.2,
"SimMode": "Car"
}

위 내용은 가장 기본 형태의 셋팅입니다.

아래 내용은 설정 가능한 내용들입니다.

settings.json을 수정 후에는 simulator를 재실행해야 합니다.

"Map"의 경우, 로딩되는 맵을 의미합니다.

"Map": "10" > 베이직: 대회에서 사용

"Map": "30" > 스피드 (장애물 없음) : 연습용

"Map": "31" > 스피드 (장애물 있음): 대회에서 사용

"Map": "60" > 싸피 (장애물 없음) : 연습용

"Map": "61" > 싸피 (장애물 있음): 대회에서 사용

"Map": "70" > 싸피 (장애물 없음). 저사양 PC 용: 연습용

"Map": "71" > 싸피 (장애물 있음). 저사양 PC 용: 개인 로컬 PC에서 사용

"Map" : "160" > 독일 (장애물 없음) : 연습용

"Map" : "161" > 독일 (장애물 있음) : 대회에서 사용

"BGM": true > 배경음악 on, off. 디폴트는 false

"EngineSound": false > 차량의 엔진 사운드 on, off. 디폴트는 false

json
{
"SettingsVersion": 1.2,
"SimMode": "Car",
"BGM": true,
"EngineSound": false,
"Algo": {
"Map": "10"
},
"Vehicles": {
"Car1": {
"VehicleType": "PhysXCar",
"X": 0, "Y": 0, "Z": 0
}
}
}

첨부파일
총 1 개 3.12 KB / 50MB
settings.zip (3.12 KB)
