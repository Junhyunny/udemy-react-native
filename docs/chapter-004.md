
## Chapter 4. A Glance Under The Hood of React Native

* React / React Native 어플리케이션을 개발할 때 React 코드처럼 개발한다.
* React 방식으로 개발된 코드는 네이티브 어플리케이션으로 컴파일, 빌딩된다.
    * JSX 코드 같은 컴포넌트들이 네이티브 UI 요소로 컴파일된다.
* 예를 들면 다음과 같이 각 플랫폼 별로 요소들이 매칭된다.

| Web Browser | Android | iOS | React Native JSX |
|:-:|:-:|:-:|:-:|
| div | android.View | UIView | View |
| input | EditText | UITextField | TextInput |

* JavaScript 비즈니스 로직 코드는 UIElement처럼 컴파일되지 않는다.
    * React Native에 의해 호스팅되는 JavaScript 스레드에 의해 실행된다.
    * 비즈니스 로직은 JavaScript 코드로서 실행되며 React Native에 의해 Android, iOS 플랫폼과 통신된다.