# H-Bag-Shop 🛍️

React로 만든 가방·의류 쇼핑몰 프로젝트입니다.
상품 탐색부터 장바구니까지의 흐름과, 자주 묻는 질문에 답하는 FAQ 챗봇을 구현했습니다.

🔗 **배포 사이트**: https://0l4h1e3.github.io/H-Bag-Shop/

<!-- 메인 화면 스크린샷을 넣으세요: ![H-Bag-Shop 메인 화면](./screenshot.png) -->

<img width="800" height="1845" alt="hbagshop-main" src="https://github.com/user-attachments/assets/bf02cdb6-0f26-4b27-bafa-0b87ec4d0282" />


## 프로젝트 소개


| 항목 | 내용 |
| --- | --- |
| 프로젝트명 | H Bag Shop |
| 제작 기간 | 2026.10 ~ 2026.11(28일) |
| 제작 인원 | 1인 (기획 · 디자인 · 개발) |
| 배포 | GitHub Pages |

## 주요 기능

- **상품 목록 · 상세** : 상품 탐색과 제품 상세 정보(상품 디테일 사진 등)확인
- **장바구니** : 담기 · 수량 변경 · 삭제
- **FAQ 챗봇** : OpenAI API 없이 JSON 데이터를 기반으로 자주 묻는 질문에 응답
- **반응형 레이아웃** : 모바일 · 태블릿 · PC 대응
- **문의사항 · 공지사항** : 글작성 · 수정 · 삭제 · 검색


## 기술 스택

- **Framework** : React
- **Build Tool** : Vite
- **Style** : SCSS, CSS
- **Deploy** : GitHub Pages

## 폴더 구조

> 이 저장소는 **배포용 빌드 결과물**입니다. (`npm run build`로 생성된 파일)

```
H-Bag-Shop
├─ assets/        # 빌드된 JS · CSS · 이미지
├─ index.html     # 진입 파일
├─ favicon.svg
├─ icons.svg
└─ README.md
```

<!-- 소스 코드 저장소가 따로 있다면 링크를 넣으세요: 🔗 소스 코드: https://github.com/0l4h1e3/저장소명 -->

## 실행 방법

소스 코드 기준으로 실행하는 방법입니다.

```bash
# 1. 패키지 설치
npm install

# 2. 개발 서버 실행
npm run dev

# 3. 빌드
npm run build
```

## 배포 방법

1. `vite.config.js`에 저장소 이름을 `base`로 지정합니다.
   ```js
   export default defineConfig({
     base: "/H-Bag-Shop/",
     plugins: [react()],
   });
   ```
2. `npm run build`로 `dist` 폴더를 생성합니다.
3. `dist`의 내용을 GitHub 저장소에 올리고, **Settings → Pages**에서 배포 브랜치(`main`)를 지정합니다.

## 만든 사람

**이하은 (Lee Ha Eun)** · UI/UX 디자이너
- Portfolio : <!-- 포트폴리오 주소 -->
- Email : prettlee04@naver.com
