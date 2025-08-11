# AI채팅 과의존 자가체크 (1분 컷)

이 저장소는 단일 HTML 페이지로, GitHub Pages로 바로 배포할 수 있습니다.

## 빠른 배포
1. 이 리포를 GitHub에 새 **Public** 저장소로 만들고(예: `ai-chat-scale`), 파일 업로드로 `index.html`과 `.nojekyll`을 추가합니다.  
   - 또는 이 ZIP을 그대로 업로드한 뒤 **Code → Upload files** 사용.
2. 저장소 **Settings → Pages**로 이동합니다.
3. **Source: Deploy from a branch**, **Branch: `main` / **`/(root)`**를 선택하고 저장.
4. 1~2분 내에 **Pages** 섹션에 배포 링크가 표시됩니다.  
   - 주소 예시: `https://<username>.github.io/<repo>`

## 로컬 미리보기
아래 중 하나 사용:
- (간단) 더블클릭으로 브라우저에서 `index.html` 열기
- (서버) Python: `python -m http.server` → `http://localhost:8000`

## 참고
- `.nojekyll` 파일은 GitHub Pages가 정적 파일을 그대로 서빙하도록 해줍니다.
- 커스텀 도메인을 쓰려면 `Settings → Pages → Custom domain`에서 연결하고, 저장소 루트에 `CNAME` 파일(내용: 도메인) 추가.
