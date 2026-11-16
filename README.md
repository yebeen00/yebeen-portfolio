# YU YEBEEN — Portfolio

비주얼·콘텐츠 디자이너 유예빈의 포트폴리오 원페이지 사이트입니다.
빌드 과정 없이 `index.html`과 `assets/` 폴더만으로 동작하는 정적 사이트예요.

## GitHub Pages로 공개하기

1. GitHub에서 새 저장소를 만듭니다 (예: `yebeen-portfolio`, Public).
2. 이 폴더의 파일을 올립니다. 아래 두 방법 중 하나를 고르세요.
   - **웹에서 올리기:** 저장소의 **Add file → Upload files**에 `index.html`, `assets` 폴더, `README.md`를 끌어다 놓고 **Commit changes**를 누릅니다.
   - **터미널에서 올리기:** 이 폴더는 이미 git 저장소이고 첫 커밋이 되어 있어요.
     ```bash
     git remote add origin https://github.com/<아이디>/yebeen-portfolio.git
     git push -u origin main
     ```
3. 저장소의 **Settings → Pages**에서 **Source: Deploy from a branch**, **Branch: `main` / `/ (root)`**를 고르고 저장합니다.
4. 1~2분 뒤 `https://<아이디>.github.io/yebeen-portfolio/`에서 사이트가 열립니다.

## 구성

| 경로 | 내용 |
|---|---|
| `index.html` | 페이지 전체 (HTML, CSS, JS) |
| `assets/img/` | 斌·武 한자 이미지 |
| `assets/work/` | 작업 이미지 |
| `assets/yu-yebeen-portfolio-2026.pdf` | 포트폴리오 PDF |
| `.nojekyll` | GitHub Pages가 파일을 그대로 서비스하도록 하는 빈 파일 |

폰트(Instrument Serif, IBM Plex Mono, Inter Tight, Wanted Sans)와 라이브러리(Three.js, Lenis)는 CDN에서 불러옵니다.

## 로컬에서 보기

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 엽니다. 파일을 더블클릭해 `file://`로 열면 파티클이 보이지 않을 수 있어요.

© 2016–2026 Yu Yebeen
