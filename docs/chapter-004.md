
## Chapter 4. A Glance Under The Hood of React Native

* React / React Native 어플리케이션을 개발할 때 React 코드처럼 개발한다.
* React 방식으로 개발된 코드는 네이티브 어플리케이션으로 컴파일, 빌딩된다.
    * JSX 코드 같은 컴포넌트들이 네이티브 UI 요소로 컴파일된다.
* 예를 들면 다음과 같이 각 플랫폼 별로 요소들이 매칭된다.

| Web Browser | Android | iOS | React Native JSX |
|:-:|:-:|:-:|:-:|
| div | android.View | UIView | View |
| input | EditText | UITextField | TextInput |
| div | android.View | UIView | View |

* 