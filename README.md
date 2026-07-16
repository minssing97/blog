# Travel & AI Workspace

여행용 웹 대시보드와 AI 콘텐츠 제작 도구를 모아 둔 정적 웹 프로젝트입니다.

## 시작하기

- 통합 사이트 모음: [`portal.html`](portal.html)
- 기본 진입 페이지: [`index.html`](index.html)

GitHub Pages에서는 저장소 루트의 `index.html`이 중앙아시아 여행 대시보드로 열립니다. 다른 화면은 메인 상단의 **사이트 모음** 메뉴에서 이동할 수 있습니다.

## 페이지 구성

| 페이지 | 용도 |
| --- | --- |
| `index.html` | 중앙아시아 대륙종단 2026 메인 여행 대시보드 |
| `middle_asia_2026.html` | 메인 대시보드의 보존용 동기화 사본 |
| `브리즈번_index.html` | 브리즈번 힐링 여행 대시보드 |
| `ai_news.html` | AI 뉴스 수집 및 분석형 블로그 초안 도구 |
| `ai_blog_posting.html` | 주제 추천부터 본문 생성까지 지원하는 AI 포스팅 도구 |
| `portal.html` | 위 페이지를 연결하는 통합 사이트 모음 |

`brisbane.html`은 브리즈번 대시보드의 이전 간소화 버전으로 보존합니다.

## 로컬 실행

PowerShell에서 저장소 폴더를 연 뒤 다음 명령을 실행합니다.

```powershell
python -m http.server 8080
```

브라우저에서 `http://127.0.0.1:8080/portal.html`을 열면 전체 페이지를 확인할 수 있습니다.

## 참고

- 여행 체크리스트와 가계부 데이터는 브라우저 `localStorage`에 저장됩니다.
- 날씨·환율·지도와 AI 도구는 인터넷 연결이 필요할 수 있습니다.
- AI 페이지는 사용자가 입력한 Google Gemini API 키를 브라우저에서 사용합니다.
