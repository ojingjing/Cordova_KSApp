# Cordova_KSApp

- Cordova
- Html
- Css
- Api
- JavaScript
---

Cordova(모바일 애플리케이션을 개발하기 위한 오픈 소스 프레임워크) 를 이용하여 경성대학교 소프트웨어학과 사이트를 App으로 개발 하였다.    

## 설정  
```
npm install -g cordova

cordova create BrowerTest

cordova run browser
```
<img width="355" alt="image" src="https://github.com/ojingjing/Cordova_KSApp/assets/48702158/9b6ed746-a750-47b2-873a-c52ee34989ff">      
이 화면이 뜨면 Cordova 연결 성공     

```
cordova platform add android

cordova build android

cd platforms/android/app/build/outputs/apk/debug/ ##이 파일 에 debug 파일 애뮬레이터로 ㄱㄱ
cordova run android --list ## 실행 가능한 애뮬레이터 확인하는 명령어

cordova emulate android   ## 가상 단말기 실행

cordova run android  ## 실물 단말기 실행 
```
## 애뮬레이터로 구현한 결과물   
<img width="355" alt="image" src="https://github.com/ojingjing/Cordova_KSApp/assets/48702158/f5c7384a-da1f-4db9-977d-2935dc196cd8">
   

## 앱 소개  
- Home
- 학과소개
- 교육목표및 인재상
- 이수교육도 및 교육

## 결과물   

<img width="355" alt="image" src="https://github.com/ojingjing/Cordova_KSApp/assets/48702158/ae8dbab8-cd9e-425a-88f5-ffab4bfe6821">

