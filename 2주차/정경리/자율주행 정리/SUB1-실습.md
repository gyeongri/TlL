
1. talker ↔ listener
	rosrun: python 코드 실행 명령어
	`rosrun {실행할 코드가 있는 패키지 명} {실행할 노드명(python파일명)}`
	 → `` rosrun ssafy_1 talker.py
		 "hello ssafy"라는 string을 publish함.
	 → ` rosrun ssafy_1 listener.py`
		 "hello ssafy"를 수신하여 출력

2. Launch
	roslaunch: 패키지에 있는 launch 파일 실행 명령어
	`roslaunch {실행할 코드가 있는 패키지명} {실행할 launch 파일명}`
	roslaunch ssafy_1 talker_listener_1.launch
	 → talker.py와 listener.py를 동시에 실행하는 파일 실행


3. publish, subscribe
	여러 정보(string, uint8, uint32) 가 담긴 메시지를 publish, subscribe 하는 기능
	my_name_talker.py ↔ my_name_listener.py
	