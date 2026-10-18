# ll-client

논술 학습 앱의 Expo · React Native · TypeScript 클라이언트입니다.

## 시작하기

Expo SDK 58, Node.js 24 LTS, Yarn 4.18.1을 사용합니다.
패키지는 `node_modules` 방식으로 설치합니다.

```bash
corepack enable
yarn install --immutable
yarn start
```

```bash
yarn ios
yarn android
yarn typecheck
```

실기기의 Expo Go는 SDK 58 지원 버전이 필요합니다. 지원 버전이 없으면 Expo 개발 빌드를 사용합니다.

## 기본 패키지

- Expo, React, React Native
- TypeScript
- react-native-webview: 앱 안에서 웹 화면 표시
- react-native-reanimated, react-native-worklets: 애니메이션
- react-native-gesture-handler: 터치 및 드래그 제스처

현재는 패키지와 실행에 필요한 최소 설정만 포함하며, 앱은 빈 화면으로 시작합니다.
