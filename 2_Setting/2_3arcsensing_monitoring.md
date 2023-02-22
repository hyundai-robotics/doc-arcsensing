﻿# 2.3 아크센싱 모니터링

(1)	모니터링 실행

모니터링 항목 중 ‘26: 아크센싱’를 선택하면 아크센싱 모니터링이 실행됩니다. 이 항목은 아크센싱 라이선스가 유효한 상태에서만 활성화 됩니다.


(2)	모니터링 항목 설명

 <p align="center">
 <img src="../_assets/2_6.png" width="60%"></img>
 <em><p align="center">그림 2.6 아크센싱 모니터링 창 세부 설명</p></em>
</p>


좌우 추종: 좌우방향으로 센싱에 의한 추종 속도, 거리, 전류차 방식으로 계산된 보정할 좌우 거리를 표시합니다.

상하 추종: 상하방향으로 센싱에 의한 추종 속도, 거리, 용접선 방식으로 계산된 보정할 상하 거리를 표시합니다.

XYZ 추종: 원래 궤적대비 현재까지 추종한 거리를 Base 좌표계 X, Y, Z 방향 거리로 표시합니다.

센싱 데이터

BC: 상하방향 센싱 기준 전류
CC: 상하방향 센싱 용 현재 구간의 중앙 부분 전류.
LR: 현재 구간의 위빙 끝 영역 전류
WC: 용접기의 용접 전류
Mode: 현재 적용 중인 지연시간, 모드 번호

상하방향 기준전류는 사용자가 입력하거나 용접 시작 영역에서 중앙 부분 전류를 일정 구간 동안 평균한 값으로 설정합니다.
상하방향의 센싱은 기준전류와 현재 측정 전류를 차이를 이용하여 보정할 상하방향 거리를 계산합니다. 따라서 기준 전류를 높이면 토치와 모재가 가까워지고 기준 전류를 낮추면 토치와 모재가 멀어집니다.

위빙 데이터: 현재 위빙폭, 위빙 주파수, 지연시간, 모드 번호를 표시합니다.

멀티패스: 저장된 멀티패스 데이터의 현재/전체 카운트, 시프트 거리, 각도를 표시합니다.
