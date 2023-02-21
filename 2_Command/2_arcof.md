﻿# 2.2 arcoff


- 설명 
    
    ```arcoff```는 Arc용접을 종료하는 명령어 입니다. 이 명령어는 4가지 형태로 사용될 수 있습니다. 단, 설정된 용접기에서 지원하지 않는 명령어는 사용할 수 없습니다.



- 문법
  
    - ```arcoff```  
    - ```arcoff``` welder=2, delay=30

- 파라미터
  
   ① welder 조건번호
     - 내용 : 용접기를 2대 사용하는 경우 off시킬 용접기 번호를 설정합니다.
     - 범위 : 1~2
  
   ② delay 지연시간
     - 내용 : 용접기를 2대 사용하는 경우 off시킬 지연시간을 설정합니다.
     - 범위 : 0~2
</br>  

- 사용 예

 ```python
    arcoff                    #특별한 종료처리 없이 Arc 용접을 종료 함
    arcoff welder=2, delay=1  #2번째 용접기 아크를 1초 후 off 
```

- 세부 설명  
  [[5장 Arc용접 조건 편집]](../5_Condition_editing/README.md) 참고


</br>
</br>

{% hint style="warning" %}
[**주의**]   
 -	디지털 용접기를 사용하기 위해서는 『시스템』 → 『5: 초기화』→ 『3: 용도설정』대화상자의 ‘아크용접’을 디지털로 설정해야 합니다.

{% endhint %}