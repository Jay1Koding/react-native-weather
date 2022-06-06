### 브라우저에서 React 어플리케이션을 만들 수 있게 해주는 온라인 코드 에디터

[snack](https://snack.expo.dev/)

### React Native rules

1. 웹사이트가 아니다! Not HTML // View로 만듬
2. React Native에 있는 모든 text는 text component에 들어가야함
3. View에는 style이 있다
4. StyleSheet.create는 object를 생성함
5. status-bar는 3rd-party package다

[RN dev](https://reactnative.dev/docs/components-and-apis)

### React Native Packages?

- 기본적으로 개발자들에게 최대한 많은 APIs와 Components를 제공하려 했음
- 유지 관리와 업데이트의 어려움을 깨달음
- 서비스의 규모를 줄이고 Community packages를 써야함

### Component VS APIs

- Component는 화면에 렌더링할 항목 //
  - ex ) View
- API는 자바스크립트 코드 // 운영 체제와 소통하는 것
  - Vibration
- Expo는 RN의 일부 Component와 APIs를 복제하고 개선함
  - ex ) 기능은 거의 같지만 함수명이 다름
  - 대부분의 필요 기능들은 구현해놓음

[Expo SDK](https://docs.expo.dev/versions/latest/)
