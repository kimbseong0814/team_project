# [Project] SMART_HOME

## 스마트홈 시스템 개요
본 프로젝트는 에어컨과 환풍기를 중심으로 한 스마트홈 기초 제어 시스템을 구현하는 것을 목표로 진행되었다. 아두이노 및 STM32 플랫폼을 기반으로 한 무선 제어 구조를 구성하고, Raspberry Pi를 서버로 설정하여 Wi-Fi 및 Bluetooth를 통한 양방향 통신을 구현하였다.

각 디바이스는 실시간 명령 송수신이 가능하며, 사용자의 선호 설정에 따른 자동화 기능과 외부에서의 원격 제어가 가능하도록 설계되었다. 기본 제어 외에도, 가습기, 공기청정기, 침입 감지, 경고 알람 등 다양한 센서 및 모듈을 연동할 수 있는 유연한 구조로 구성하여, 향후 다양한 스마트 가전을 통합 제어할 수 있는 기반을 마련하였다.

## 담당 역할
1. Arduino – 버튼을 이용한 MOTOR 제어
2. Arduino – Auto / Manual에 따른 LED On / Off
3. Sensor.c – 버튼 입력을 통한 sensor 코드 제어

## 📷 시스템 구성도

![스마트홈 구성도](https://github.com/사용자이름/레포지토리이름/blob/브랜치명/이미지경로.png?raw=true)


## 🎬 SMART_HOME 시연 영상

### 📽 발표 영상  
[![라즈베리파이 영상](http://img.youtube.com/vi/jWnwy2fSu9o/0.jpg)](https://www.youtube.com/watch?v=jWnwy2fSu9o)

### 📽 발표 영상  
[![아두이노_STM32 영상](http://img.youtube.com/vi/SP8eZF5cb_0/0.jpg)](https://www.youtube.com/watch?v=SP8eZF5cb_0)







