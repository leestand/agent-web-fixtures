# Agent Web Fixtures

AI Agent의 웹 조작 능력을 평가하기 위한 테스트용 정적 웹페이지 저장소입니다.

이 저장소는 다음 평가 시나리오를 테스트하기 위해 만들어졌습니다.

- 링크 접근 가능 여부 확인
- 웹페이지 내 이미지 식별
- 필요한 이미지 다운로드
- 이미지 파일명 변경
- 이미지 출처 링크 반영
- 다운로드한 이미지를 활용한 게시글 작성

## GitHub Pages URL

배포 후 아래 형식의 URL로 접근할 수 있습니다.

```text
https://leestand.github.io/agent-web-fixtures/
```

## Test Pages

- `/product-page.html` — 제품 이미지 4개가 포함된 테스트 페이지
- `/newsletter-brief.html` — 제품 소개 게시글 작성을 위한 브리프 페이지

## Test Images

- `main_product.svg` — 메인 제품 이미지
- `usage_scene.svg` — 사용 장면 이미지
- `detail_cut.svg` — 상세 컷 이미지
- `unrelated_banner.svg` — 평가에서 제외해야 하는 무관한 배너 이미지

## Evaluation Purpose

이 저장소는 AI Agent가 웹페이지에서 필요한 이미지만 식별하고, 요청한 파일명으로 저장한 뒤, 이미지 출처를 포함한 콘텐츠를 생성할 수 있는지 평가하기 위한 용도입니다.

실제 회사 데이터, 실제 제품 이미지, 개인정보는 포함하지 않습니다.
