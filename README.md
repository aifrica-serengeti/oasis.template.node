# Express App - 빠른 시작 템플릿

이 프로젝트는 간단한 **Express** 애플리케이션을 통해 빠르게 시작할 수 있는 템플릿입니다. 환경 변수를 사용하여 응답 메시지(`TARGET`) 및 서버 포트(`SERVER_PORT`)를 유연하게 설정할 수 있습니다.

## 기능

- 기본 경로 `/`로 요청 시, 환영 메시지를 출력합니다.
- 환경 변수 `TARGET`에 설정된 값에 따라 환영 메시지가 동적으로 변경됩니다. 기본값은 "World"입니다.
- `SERVER_PORT` 환경 변수를 통해 서버의 포트를 설정할 수 있으며, 기본 포트는 `8080`입니다.

## 설치

### 1. 필수 패키지 설치

`package.json` 파일에 명시된 의존성을 설치하기 위해 다음 명령어를 사용합니다.

```bash
npm install
```

## 실행 방법

### 1. 기본 설정으로 실행

기본적으로 실행하면 `Hello World!`라는 환영 메시지가 출력됩니다. 포트 번호는 **8080**으로 설정됩니다.

```bash
npm run start
```

### 2. 환경 변수를 지정하여 실행

#### 환경 변수 `TARGET` 설정:

환경 변수 `TARGET`에 원하는 값을 설정하면, 해당 값이 메시지에 포함됩니다.


#### 실행:

환경 변수를 설정하고 애플리케이션을 실행합니다.

```bash
npm run start
```


## How to Test

1. 기본적인 **Node.js** 환경을 세팅한 후 애플리케이션을 실행하세요.

```bash
npm run start
```

2. 브라우저에서 애플리케이션에 접속합니다:


3. 웹 페이지가 정상적으로 로드되고 `Hello World!` 메시지가 표시되는지 확인합니다.


## 커스터마이징

- **환영 메시지 변경**: `TARGET` 환경 변수를 수정하여 동적으로 출력되는 환영 메시지를 변경할 수 있습니다. 예: `TARGET=NodeJS`로 설정하면 `Hello NodeJS!` 메시지가 출력됩니다.
- **포트 변경**: `SERVER_PORT` 환경 변수를 통해 실행 포트 번호를 변경할 수 있습니다. 기본값은 **8080**입니다.
