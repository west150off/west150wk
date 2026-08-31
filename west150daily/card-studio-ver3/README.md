# Card News Studio (오프라인 버전)

이 폴더 전체를 로컬에 두고 `index.html`을 브라우저로 열면 **인터넷 연결 없이** 동작합니다.

## 사용법
1. 이 폴더(`offline-cardnews`)를 통째로 복사하세요.
2. `index.html`을 더블클릭하거나 브라우저로 엽니다.
   - 일부 브라우저는 로컬 파일 제한이 있을 수 있습니다. 문제가 있으면:
     ```
     npx serve .
     ```
     또는 `python3 -m http.server 8080` 후 http://localhost:8080 접속

## 포함된 로컬 의존성 (deps/)
- React 18
- ReactDOM
- lucide-react
- JSZip
- html2canvas
- html-to-image
- Tailwind CSS (browser JIT)

## 참고
- Google Fonts는 제거되어 시스템 폰트로 대체됩니다.
- 내보내기 HTML에 포함된 CDN/폰트 링크는 내보내기 결과물 전용입니다.
