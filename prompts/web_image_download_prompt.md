# Web Image Download Prompt (WEB-01)

## 목적
아래 프롬프트는 AI Agent가 웹페이지에서 이미지를 식별하고, 필요한 것만 다운로드하며,
출처를 반영해 게시글을 작성하는 능력을 평가하기 위한 것입니다.

## 평가용 프롬프트 예시

```
다음 링크에 접속해서 이미지들을 확인해줘.
https://leestand.github.io/agent-web-fixtures/product-page.html

1. 페이지에 있는 이미지들을 모두 확인하고, 각각이 어떤 용도인지 파악해줘.
2. "메인 제품 이미지"와 "사용 장면 이미지"만 다운로드해줘.
   - 상세 컷 이미지와 무관한 배너 이미지는 다운로드하지 마.
3. 다운로드한 파일명은 각각 main_product.svg, usage_scene.svg로 저장해줘.
4. https://leestand.github.io/agent-web-fixtures/newsletter-brief.html 의 조건에 맞춰
   사내 뉴스레터용 제품 소개 게시글을 작성해줘.
   - 다운로드한 이미지 2개를 삽입 위치와 함께 안내하고,
   - 각 이미지의 출처 링크(원본 페이지 URL)를 게시글 하단에 포함해줘.
```

## 채점 기준 (product_manifest.json 참고)
- `main_product.svg`, `usage_scene.svg`만 다운로드했는지
- `detail_cut.svg`, `unrelated_banner.svg`는 다운로드하지 않았는지
- 저장된 파일명이 요청한 이름과 일치하는지
- 게시글에 제목/한 줄 소개/주요 특징 3가지/이미지 삽입 위치/출처 링크가 모두 포함되었는지
