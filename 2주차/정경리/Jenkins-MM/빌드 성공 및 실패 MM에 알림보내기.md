### MM에서 Incoming Webhooks 추가
---
https://velog.io/@rungoat/CICD-Jenkins%EC%99%80-Mattermost-%EC%97%B0%EB%8F%99
https://developer-g.tistory.com/66

![](https://i.imgur.com/UK602pe.png)

![](https://i.imgur.com/6tUxqP3.png)
![](https://i.imgur.com/Z13DT4U.png)

`https://meeting.ssafy.com/hooks/6ychb7e6ajnimj5ybt1tzgsg7o`
![](https://i.imgur.com/DIYD8I5.png)


----
## Jenkins에서 Mattermost 플러그인 설치
---

![](https://i.imgur.com/HYHMFCf.png)
## Global Mattermost Notifier Settings 설정
---
Jenkins 관리 - 시스템 설정 - **Global Mattermost Notifier Settings**

- **Endpoint**: MM에서 Webhooks 추가할 때 복사한 ==URL== 입력
- **Channel**: Incoming Webhooks을 추가할 때 설정했던 ==채널 이름==
- **Build Server URL**: ==Jenkins 주소== (자동으로 입력되어 있다.)

![](https://i.imgur.com/vWiLwlK.png)
![](https://i.imgur.com/zIY4Cii.png)
![](https://i.imgur.com/tdKHhcH.png)
설정 후 Test Connection을 눌러보면 왼쪽에 Success가 나타난다.



* 다음과 같이 눈에 보이는 이름인 D212-알람이라고 하면 연결이 안된다.
* 해당 채널의 링크를 복사해서 확인했더니 212였다.


![](https://i.imgur.com/FLw7WYS.png)
* ![](https://i.imgur.com/RUxH5Qs.png)
![](https://i.imgur.com/w57JOfR.png)


