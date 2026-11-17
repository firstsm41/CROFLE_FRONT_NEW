# CROFLE_FRONT_NEW

Vue 3 기반 크라우드펀딩 프론트엔드 프로토타입입니다. 상품 탐색, 회원 화면, 마이페이지와 관리자 화면을 포함합니다.

## 실행

```bash
npm ci
npm run dev
```

## 빌드

```bash
npm run build
npm run preview
```

## 환경 설정

```bash
cp .env.example .env
```

`VITE_API_URL`을 준비한 백엔드 주소로 바꿉니다. `VITE_` 환경 변수는 브라우저에 공개되므로 비밀 키를 넣지 않습니다.
`.env`는 로컬에서 관리하며 예시 파일만 Git으로 공유합니다.

## 폴더 구조

```text
.
├── index.html
├── src/
│   ├── api/          # HTTP API 클라이언트
│   ├── assets/       # 이미지와 스타일
│   ├── components/   # 재사용 UI
│   ├── layouts/      # 공통 화면 틀
│   ├── router/       # 화면 경로
│   ├── store/        # 클라이언트 상태
│   └── views/        # 페이지
├── public/           # 그대로 제공하는 정적 파일
└── docs/             # 개발 참고 문서
```

[로컬 페이지 안내](docs/local-routes.md)
