# IOT-Project

## Describe
카메라 모듈을 설치했다면,카메라를 인식시켜줘야 합니다.
라즈비안 OS에서는 raspi-config라는 프로그램을 활용하여 간단하게 설정할 수 있는데, Ubuntu에서는 제공을 하지 않기 때문에, 직접 설정을 해줘야 합니다.

* PATH 이동
  / 디렉토리로 이동하여 /dev로 이동 
![image](https://user-images.githubusercontent.com/49769190/181157238-03638886-7213-4b48-b782-61fb85e65846.png)

* ls 현재 디렉토리의 목록을 파악
![image](https://user-images.githubusercontent.com/49769190/181157371-bc572449-c1e9-4f4f-a14c-54fa35867f02.png)
 카메라는 보통 'video0'이다.
raspi-config /boot/firmware
