# 우수현 포트폴리오 (GitHub Pages용, 빌드 불필요)

이 폴더를 GitHub 저장소에 올리고 **Settings → Pages → Deploy from a branch** 에서 `main` 브랜치의 `/ (root)`를 선택하면 바로 사이트가 배포됩니다.

## 파일 구성
- `index.html` : 메인 페이지 (Tailwind CDN 사용, 빌드 불필요)
- `pdf-viewer.html` : pdf.js 뷰어 페이지 (CDN 사용)
- `docs/bitcoin-etf.pdf` : 프로젝트에서 열리는 PDF 파일 (포함됨)

## 사용법
1. 이 폴더 전체를 새 레포지토리에 업로드
2. (선택) `docs/bitcoin-etf.pdf` 를 교체하거나 더 추가
3. GitHub → 레포 → Settings → Pages → Branch: `main`, Folder: `/ (root)` → Save

완료 후 페이지 주소는 보통 `https://<username>.github.io/<repo>/` 입니다.
