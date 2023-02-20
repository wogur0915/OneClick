# OneClick


## 소개

OneClick 프로그램은 충북대학교 컴퓨터공학과를 재학중인 학생들이 실습실이나 가정에서 학교 관련 홈페이지를 이용할 때 마다 매번 로그인 해야하는 불편함을 줄이고, 실습실에서 로그아웃을 하지 않아 정보 유출이 되는 문제를 방지하며 간단한 오락을 제공하기 위해 기획 및 제작을 진행하게 된 PC프로그램 입니다.



## 목적
- 사용자에게 학교 관련 홈페이지의 자동 로그인 기능을 제공, 비 로그인 시 단순 링크 기능 제공 (제공되는 사이트 : 
- 제공받은 실시간 화분 습도 상태에 따라 일정 습도 이하의 '수분 부족' 상태 시 Push 알림을 통해 사용자에게 수분 공급의 필요 알림 제공
- 키우는 식물에 대하여 간단한 메모나 성장 일기 형식으로 사용할 수 있도록 '식물 일지' 기능과 이에 포함된 사진을 보관할 수 있는 식물 앨범 기능 제공
- 농촌진흥청 농업기술포털 '농사로' 에서 제공하는 실내정원식물 관리에 관한 다양한 정보를 API를 통하여 사용자가 종 검색시 즉시 제공


-----

## 의존성
```
[ OS ]
Android >= 11.0 (권장사양)
Android >= 5.0 Lollipop (최소사양)

[ Language ]
Python

[Library]
google-services >= 4.3.3

[Program]
Visual Studio Code

```
-----

## 설치방법

#### Git 환경
```
git clone https://github.com/wogur0915/GreenWater
```


#### Windows 환경
- Code Zip 파일 다운로드 및 압축 해제
- Arduino IDE 를 실행하여 arduinoCodes 폴더 내의 soil_moisture_with_bluetooth 폴더에 있는 soil_moisture_with_bluetooth.ino 실행 후 아두이노 장치에 업로드
- Android Studio 로 실행 후 내장되어있는 Emulator 또는 안드로이드 기기에 연결하여 실행

-----

## 사용 방법

- 1. Arduino IDE를 통해 코드가 업로드된 아두이노 하드웨어에 전원을 연결한 한 후 토양습도센서를 측정을 원하는 화분에 삽입
- 2. GreenWater 앱 실행 후, 앱 내 설정 메뉴에서 블루투스 기기검색을 통해 아두이노 연결
- 3. GreenWater 앱의 화분 모니터링 메뉴를 통해 화분의 습도상태 확인 및 습도 저하 알림 서비스 제공 받음
- 4. 식물에 대헌 간단한 메모나 등을 '식물 일지' 를 통해서 작성
- 5. 식물 도감 메뉴에서 키우는 식물 검색 후 관련 정보 습득


## 실행 화면

![KakaoTalk_20221210_204433706](https://user-images.githubusercontent.com/34836246/206853405-a1ad426b-dde9-4ccc-b3f2-08b2641f284e.jpg)
![KakaoTalk_20221210_203025133_06](https://user-images.githubusercontent.com/34836246/206853426-7a7c473e-31ea-4d54-acea-ce94d2a9de21.jpg)

-----

## 연락처 (Contributors)

| |임재혁|이채운|송영은|김민서|
|------|----|----|----|----|
|GitHub| [wogur0915](https://github.com/wogur0915)              |      [dlcodns](https://github.com/dlcodns)         |      [songyeongeun](https://github.com/songyeongeun)         |      [KIMSSI22](https://github.com/KIMSSI22)         |

-----

## License

```
The MIT License (MIT)

Copyright (c) 2022 Team-GiveComplements

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
