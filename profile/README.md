## Next.js 스터디 Overview

### 📆 스터디 일정

- **스터디 요일:** 일요일 / 화요일 / 금요일
- **진행 방식:**
    
    각 스터디 요일 전에 **정해진 분량의 Next.js 공식문서**를 읽고 정리합니다.
    

---

### 💻 스터디 진행 방식

1. **브랜치 생성**
    - 브랜치 이름 규칙:
        
        ```
        docs/{본인이름}
        ```
        
        예시:
        
        ```
        docs/yuseoung
        ```
        
2. **정리 내용 작성**
    - 공식문서를 학습 후, 자신의 언어로 핵심 내용을 정리합니다.
    - 정리 파일은 Markdown(`.md`) 형식으로 작성합니다.
    - 폴더 구조 예시:
        
        ```
        /docs
          ├── yuseoung/
          │    ├── nextjs-fundamentals/
          │    │    ├── routing.md
          │    │    ├── rendering.md
          │    │    └── data-fetching.md
          │    └── nextjs-advanced/
          │         └── caching.md
        ```
        
3. **커밋 및 PR 생성**
    - 커밋 메시지 규칙:
        
        ```
        docs: {정리 주제 요약}
        ```
        
        예시:
        
        ```
        docs: Next.js Routing 정리
        ```
        
    - 각자 브랜치에서 작업을 마친 후 **PR(Pull Request)**을 생성합니다.
    - PR 제목 예시:
        
        ```
        [docs/{이름}] Next.js Rendering 정리
        ```
        
4. **리뷰 & 병합**
    - 다른 팀원이 PR을 확인하고 리뷰합니다.
    - 리뷰가 완료되면 main 브랜치로 병합합니다.

---

### 📚 참고 링크

- [Next.js 공식문서](https://nextjs.org/docs)
- [Next.js GitHub Repository](https://github.com/vercel/next.js)

---

### 🧭 목적

- 공식 문서를 기반으로 **Next.js의 핵심 개념을 깊이 이해하기**
- PR, Branch 관리 등 **협업 프로세스에 익숙해지기**
- 스터디 종료 후에는 **공식문서 요약 저장소로 활용하기**
