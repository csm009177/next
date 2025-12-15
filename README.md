## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

my-next-app/
├── node_modules/         # npm 패키지들이 저장되는 디렉토리
├── .next/                # Next.js 빌드와 최적화된 결과물이 저장되는 디렉토리
├── public/               # 정적 파일들(이미지, favicon 등)을 포함하는 디렉토리
│   ├── favicon.ico       # 웹사이트의 아이콘
│   └── ...               # 기타 정적 파일들
├── src/                  # 소스 코드를 저장하는 디렉토리 (옵션, 기본적으로 없어도 됨)
│   ├── pages/            # Next.js의 특별한 폴더로, 라우트와 매핑되는 React 컴포넌트들을 포함
│   │   ├── index.js      # 메인 페이지
│   │   ├── _app.js       # 커스텀 App 컴포넌트
│   │   └── ...           # 다른 페이지 및 라우트
│   ├── components/       # 재사용 가능한 React 컴포넌트들을 저장하는 폴더 (선택적)
│   └── ...               # 기타 소스 코드 및 리소스
├── styles/               # 글로벌 스타일 및 CSS 모듈을 포함하는 디렉토리 (선택적)
│   └── global.css        # 글로벌 스타일
├── package.json          # 프로젝트의 메타데이터 및 의존성 정보
├── package-lock.json     # 설치된 패키지의 정확한 버전 정보
├── .gitignore            # git에서 무시해야 할 파일 및 디렉토리 목록
└── README.md             # 프로젝트에 대한 설명 및 문서