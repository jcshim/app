
재난 안전 앱 개발
(앱 인벤터)

국립안동대학교
심재창
목차
# 1부. AppInv의 기초
1. 앱인벤터 활용법
2. 비서 앱 (음성인식 및 폰 흔들면 말하기)-버튼, 가속도 센서, 음성인식, 음성합성
3. 사진 찍어 바로 카톡으로 보내기-카메라센서, 소셜네트워크 통신
4. 멀티미디어 응용(동물울음소리)-버튼, 영상 미디어, 음성 미디어 업로드
* 앱 아이콘 만들기: Screen > Icon
5. 실로폰 만들기-영상 미디어, 음성 미디어, 함수
6. 두더지 잡기(aia 활용하기)
* 개별 프로젝트: 유용한 앱 찾기

# 2부. 고급 응용과 와이 파이
1. 낙서장 만들기-팔레트, 색상, 슬라이드바, 나눗셈
2. 공굴리기(방향센서 활용) - 
3. 폰의 방향 센서 활용(무당벌레 움직이기)
4. 폰 데이터 베이스
5. 프로세싱 소개 및 예제 실행
6. 서버와 Wifi 통신하기 
* 에뮬레이터 활용법
* 팀 프로젝트 기획 및 계획서

# 3부. 알고리즘 및 블루투스
1. 만보계 만들기
2. 지도 앱
3. 가위바위보 게임 만들기
4. 블루투스로 아두이노 제어하기
* 팀프로젝트 진행1

# 4부. 재난 안전 프로젝트
1. XML 파싱
2. 재난 안전 팀 프로젝트
* 팀프로젝트 진행2 및 발표


# I부. 앱 인벤터
# 1. 앱 인벤터 소개
앱 개발에 필요한 내용 
1. 크롬 브라우저 
2. 구글 or Gmail “ID 및 PW” 
3. 재료 모으기(Designer) 
4. 요리하기(Blocks)
● 참고 네이버 꿀잼앱인벤터 카페 
http://cafe.naver.com/appinv 

 구글 계정 만들기
- 사용하던 구글 계정이 있으면 그대로 사용
- 안드로이드 폰: 설정>Google 계정

 앱 인벤터 사이트 접속
1. 크롬을 실행
2. Google 검색 “앱인벤터” 입력, 링크선택MIT App Inventor 2 http://appinventor.mit.edu 
3. Google ID 및 PW
4. [Create Apps!] 클릭 

5. Projects > Start New Project > Project name  
󰋫팔레트: 앱 만들기 필요한 재료
󰋫뷰어: 스마트폰 화면에 나타나는 부분
󰋫컴포넌트: 모아둔 재료를 보여줌
󰋫속성: 각 재료의 내용 변경 (예: 버튼색)
5. 재료 모으기
- User Interface: Button
- Media: TextToSpeech 
6. 재료 모은 후 오른[Blocks]를 클릭  

7. 맛보기(테스트): Connect>AI Companion>QR
8. 다운하기(설치): Build>App(...)>QR
9. 안드로이드 스마트폰, PlayStore>MIT AI2 Companion 앱 설치 및 실행
10. [푸른 바]를 선택 QR 코드로 찍기
11. 알 수 없는 출처 허용>체크
12. 앱 다운로드 및 설치

# 2. 비서 앱 만들기
[음성인식] [버튼]을 누르고 말을 하면, 음성을 인식하고 그 내용을 화면에 적는다. 폰을 흔들면 내용을 읽어 준다.
 필요한 재료(컴포넌트)
   User Interface: Button, Label
   Media: Text to Speak, Speech Recognizer 
   Sensors: Accelerometer Sensor
1. 재료 모으기 : 앱에 필요한 재료 모으기 
2. 필요한 재료를 마우스로 끌어오기

- 버튼 위치를 가운데로: Components> Screen1>AlignHorizontal>Center
- 버튼 크기 조절 Components>Button1> FontSize>32
- 버튼 이름 바꾸기: Components> Button1>Text>음성인식

3. [Blocks]에서 블록으로 코딩하기
4. 테스트하기
- 테스트용 QR 코드 만들기
- Play Store에서 “MIT AI2 Companion”
5. 다운로드하기
- 다운로드용 QR 코드 만들기
- 내 폰에 설치하기

# 3. 사진 찍어 카톡 보내기
1. [사진] 버튼을 누르면 사진이 촬영
2. <저장>을 누르면 SNS가 화면에 나옴
3. “카톡”을 선택하고 사진을 보냄.
 필요한 재료(컴포넌트)
  User Interface: Button
  Media: Camera 
 블록 만들기   

# 4. 미디어: 사운드와 그림
세 가지 동물 모양 버튼을 누르면 동물 소리가 나는 앱 만들기
 필요한 재료(컴포넌트)
   User Interface: Button, Image
   3개의 그림 파일과 2개의 소리파일 다운
     - http://cafe.naver.com/appinv/83 에 접속하여 그림파일과 소리파일을 다운로드
1. 파일 업로드: 컴포넌트 아래 Media에서 [Upload File...]을 클릭 
2. 그림파일 3개와 소리파일 3개를 업로드
   - 그림 파일은 *.png
   - 이고 소리 파일은 *.wav
 
3.[Blocks]로 가서 블록 코딩을 완성한다.

󰋫 퀴즈: 버튼을 누르면 소리가 날 때 스마트폰이 진동하게 하려면 어떻게 하면 될까요?

# 5. 실로폰 만들기
실로폰 버튼을 누르면 ‘도, 레, 미..’ 음계 소리가 나는 앱 만들기
 필요한 재료(컴포넌트)
  User Interface: Button
  Media: Player
  소리파일 (도, 레 ...시, 도), 음원 다운로드
1. http://cafe.naver.com/appinv/4339
	1.wav => 도
	2.wav => 레
	....
2. 음원 8개를 차례로 앱 인벤터에 추가, Components아래 미디어(Media)에 소리파일 추가
3. [버튼]의 속성(Properties) 을 수정
	- 버튼의 폭을 키운다. Width
	- 버튼의 색을 선택한다. 
	- 버튼의 Text에 ‘도’를 입력하면 버튼에 ‘도’가 표시된다. 
 4. 차례대로 나머지 7개를 만든다.

5. 완성된 모습 


# 6. 두더지 잡기 게임
- 앱 인벤터 코드 확장자: .aia
- 앱 인벤터 실행 파일: .apk

1. 소스코드 활용하기
다른 사람이 작성한 앱 소스코드를 내 컴퓨터에서 활용하기
단계1: 소스코드 찾기
Mole Mash 2 with Sprite Layering for App Inventor 2
https://appinventor.mit.edu/explore/ai2/molemash-2
* 홈페이지 제일 아래 부분의 “ source code”를 선택

단계2: 내 컴퓨터에 저장하기
단계3: 내 계정에 임포트(Import)하기
- Projects>Import project(.aia) from my computer

2. 내 소스코드를 컴퓨터에 저장하기

# 2부. 고급 응용, 와이 파이
# 1. 낙서장 만들기-팔레트, 색상, 슬라이드바, 나눗셈
# 2. 공굴리기(방향센서)
https://cafe.naver.com/appinv/1281
# 3. 폰의 방향 센서 활용(무당벌레 움직이기)
https://cafe.naver.com/appinv/39
# 4. 폰 데이터 베이스
https://cafe.naver.com/appinv/694
# 5. 프로세싱 소개 및 예제 실행
- 배경색 바꾸기
- 원그리기
# 6. 서버와 Wifi 통신하기 
https://cafe.naver.com/arduinocafe/4161
https://cafe.naver.com/arduinocafe/4169

* 에뮬레이터 활용법
* 팀프로젝트 기획 및 계획서
# 1. 그리기 앱 만들기

손가락으로 스마트폰에 그림을 그리자. 

시나리오
- 색상 선택하고 선의 굵기 선택 해 보자.] 
- 폰을 흔들면 그림이 지워진다.]

컴포넌트
- Canvas 캔버스
- Button 칼라 만들기
- Slider 슬라이더 (선의 크기)
- Acc..  가속도 센서

변수 추가하기: Variable => pos, col 

# 3부. 알고리즘, 블루투스
# 1. 만보계 만들기
https://cafe.naver.com/appinv/5920

# 2. 지도 검색 앱
https://cafe.naver.com/appinv/50

# 3. 가위바위보 게임 만들기
https://cafe.naver.com/appinv/3555

# 4. 블루투스로 아두이노 제어하기
https://cafe.naver.com/appinv/6083
* 팀프로젝트 진행1

# 4부. 재난안전 프로젝트

# 1. XML 파싱
https://cafe.naver.com/appinv/62

# 2. 재난 안전 팀 프로젝트
* 팀 프로젝트 진행2 및 발표

# 참고사이트
1. 앱인벤터 http://ai2.appinventor.mit.edu/ 
2. 앱인벤터 카페 http://cafe.naver.com/appinv 
3. 프로세싱 http://cafe.naver.com/processingcafe
4. 아두이노 http://cafe.naver.com/arduinocafe

국립 안동대학교 컴퓨터공학과 
심재창 교수 http://jcshim.com 
jcshim@andong.ac.kr 010-9770-5645

감사합니다.
