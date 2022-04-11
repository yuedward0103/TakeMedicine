# TakeMedicine
파이썬을 기반으로, 약 먹을 시간을 까먹는 어느 한 분을 위해 탄생한 조잡한 디스코드 봇입니다.   
정상 작동을 목적으로 새벽에 짠 코드라 상당히 더럽습니다.   
사실 조금 더 신경쓰면 이쁜 코드가 나올 수도 있지만 리팩 생각은 없습니다   
알아서 가져가서 쓰시던가 말던가...   
쓰면 쓸수록 버그가 드러나 계속 수정하고 있습니다.   

## 명령어 모음
* 약도움 : 도움 메세지 출력   
* 약언제먹어 : 알림을 받을 시간을 알려줘요.   
* 약먹을래 : 약 먹을 시간을 새로 등록해요.   
* 약안먹을래 : 등록한 시간을 지워요.   

## 구동을 위해서는 parameter.json파일이 필요합니다.
```
{
    "bot-token": 봇 토큰을 문자열로 입력하고 eatmedicine.py랑 같은 경로에 저장해주세요. 
}
```

## 사용한 패키지
~~철 지난~~ discordpy를 사용합니다.   
이 외에 따로 설치가 필요한 패키지는 없는 것으로 알고 있습니다. 아님 말고요
```
pip install discord
```
