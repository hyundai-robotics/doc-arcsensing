﻿# 2.13 posi_calib

- 설명 
    
    ```posi_calib``` 문은 입력된 프로그램 번호를 이용하여 지정한 포지셔너를 캘리브레이션 하는 명령어입니다. 이 명령은 서보축 체인지 기능과 함께 사용되며 이를 통해 로봇이 작업하는 중에도 변경된 서보축의 포지셔너를 캘리브레이션 할 수 있습니다.

- 문법
  
  	```posi_calib``` job=<프로그램 번호>, p_=<포지셔너 그룹번호>

- 파라미터
  
   ① 프로그램 번호
     - 내용 : 포지셔너 캘리브레이션이 티칭되어 있는 작업 프로그램 번호
     - 범위 : 1 ~ 9999
   
   ② 스테이션 번호 
     - 내용 : 캘리브레이션 할 포지셔너 그룹 번호
     - 종류 : S0, S1, S2, S3, All

</br>

- 사용 예
```python
   posi_calib job=9997,p_=2     #  9997.JOB 의 작업 프로그램, 2번 Station을 캘리브레이션 함
```