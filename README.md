# next-rofix-frontend

## 실행시키는 방법

### 1. Node.js 및 pnpm 설치

- Node.js 공식 홈페이지에 접속합니다: [https://nodejs.org/](https://nodejs.org/ko/download)
- LTS (장기 지원) 버전을 다운로드하여 설치하는 것을 권장합니다.

- node.js와 npm이 설치되어있는지 확인합니다.

```bash
node -v
npm -v
```

- pnpm 설치

```bash
npm install -g pnpm
```

- pnpm이 설치되었는지 확인합니다.

```bash
pnpm -v
```

### 2. 프로젝트 종속성 설치

- 프로젝트 폴더로 이동한 후 `package.json` 파일에 정의된 모든 패키지를 설치합니다.

```bash
npm install
```

### 3. 로컬 개발 서버 실행하기

- 아래 명령어를 실행하면 `http://localhost:3000` 주소에서 프로젝트 화면을 확인할 수 있습니다. 코드 수정 시 자동으로 새로고침 되므로 실시간으로 변경사항을 확인할 수 있습니다.

```bash
pnpm run dev
```

### 4. 빌드 실행

```bash
pnpm build
```

### 5. 빌드된 서버 실행

```bash
pnpm start
```
