
## Chapter 5. Creating React Native Projects: Expo CLI VS React Native CLI

* Expo CLI("Expo")
    * Third party service - free!
    * 어플리케이션 개발을 관리해준다. (managed app development)
        * 다른 도구들을 제공하기 때문에 작업하는데 쉽다.
        * Native API 사용하는 것이 쉽다.
    * `eject` 명령어를 사용해 EXPO 에코 시스템을 벗어날 수 있다. 
        * React Native CLI 개발 방식으로 넘어갈 수 있다.
    * Expo에서 제공하는 기능만 사용 가능하다.
    * 모듈을 만들어 사용하는 것이 불가능하다.
    * Native 파일을 제어할 수 없다.

* React Native CLI
    * 개발자가 원하는 모든 기능, 요소를 제어할 수 있다.
    * 다양한 라이브러리를 사용할 수 있다.
    * 네이티브 파일 제어가 가능하다.
    * 네이티브 모듈 사용이 가능하다.
    * Expo 방식에 비해 편리하지 않다.
        * 기본적인 설정이 되어 있지 않다.
        * Android Studio, XCode 모두 설치해서 빌드, 배포해야 한다.
    * Native 소스 코드(kotlin, swift)와 결합하는 것이 쉽다.
