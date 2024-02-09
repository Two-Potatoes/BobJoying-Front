# BobJoying Frontend

Bobjoing 프로젝트의 프론트엔드 저장소입니다!\
React와 TypeScript를 사용했습니다!

## 전제 조건

* Node.js와 Yarn이 설치되어 있어야 합니다.
    * Node.js는 [Node.js 공식 웹사이트](https://nodejs.org/en)에서 설치할 수 있습니다.
    * Yarn은 터미널에서 `npm install -g yarn` 명령을 통해 설치할 수 있습니다.

## 프로젝트 시작하기

1. 프로젝트 저장소 Clone
    ```bash
    git clone https://github.com/Two-Potatoes/BobJoying-Front.git
    ```

2. 의존성 설치
    ```
    yarn install
    ```

3. 프로젝트 실행
    ```
    yarn start
    ```
    이 명령어는 http://localhost:3000에서 애플리케이션을 실행합니다.


<details>
<summary>yarn이 자동 생성한 가이드(번역)</summary>

## Create React App으로 시작하기

이 프로젝트는 [Create React App](https://github.com/facebook/create-react-app)을 사용하여 구축되었습니다.

### 사용 가능한 스크립트

프로젝트 디렉터리에서, 다음을 실행할 수 있습니다:

```PHP
yarn start
```

개발 모드에서 앱을 실행합니다.\
브라우저에서 [http://localhost:3000](http://localhost:3000)을 열어서 보실 수 있습니다.

편집을 하면 페이지가 새로고침됩니다.\
또한 콘솔에서 lint 오류를 볼 수 있습니다.

```PHP
yarn test
```

대화형 감시 모드에서 테스트 러너를 시작합니다.\
더 많은 정보는 [테스트 실행하기](https://facebook.github.io/create-react-app/docs/running-tests) 섹션을 참조하세요.

```PHP
yarn build
```

프로덕션을 위한 앱을 build 폴더에 빌드합니다.\
이는 프로덕션 모드에서 React를 올바르게 번들링하고 최적의 성능을 위해 빌드를 최적화합니다.

빌드는 축소되며 파일 이름에 해시가 포함됩니다.\
앱은 배포 준비가 완료되었습니다!

더 많은 정보는 [배포](https://facebook.github.io/create-react-app/docs/deployment) 섹션을 참조하세요.

```PHP
yarn eject
```

**주의: 이것은 일방향 작업입니다. 한 번 eject하면 돌아갈 수 없습니다!**

빌드 도구와 구성 선택에 만족하지 못한다면, 언제든지 eject할 수 있습니다. 이 명령어는 프로젝트에서 단일 빌드 의존성을 제거합니다.

대신, 모든 구성 파일과 전이 의존성(webpack, Babel, ESLint 등)을 프로젝트로 직접 복사하여 모든 것을 직접 제어할 수 있게 됩니다. eject를 제외한 모든 명령어는 여전히 작동하지만, 복사된 스크립트를 가리키므로 조정할 수 있습니다. 이 시점부터는 스스로 해결해야 합니다.

`eject`를 사용할 필요는 없습니다. 큐레이션된 기능 세트는 소규모 및 중간 규모의 배포에 적합하며, 이 기능을 사용해야 한다고 느낄 의무가 없습니다. 그러나 준비가 되었을 때 이를 커스터마이징할 수 없다면 이 도구가 유용하지 않을 것임을 이해합니다.

## Learn More

[Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)에서 더 많은 정보를 알아볼 수 있습니다.

React를 배우려면, [React documentation](https://reactjs.org/)를 확인하세요..
</details>