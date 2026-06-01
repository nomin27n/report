# 활동 리포트 페이지

강의 보고서 · World IT Show 리포트 · KMUCS Job Fair 2026 리포트를 모은 정적 웹사이트입니다.

## 파일 구조

```
reports-page/
├── index.html          # 메인 페이지 (3개 블록 카드)
├── lecture-report.html # 1. 강의 보고서
├── world-it-show.html  # 2. World IT Show 리포트
├── job-fair.html       # 3. KMUCS Job Fair 2026 리포트
├── style.css           # 공통 스타일
└── README.md
```

## 로컬에서 미리보기

`index.html` 파일을 브라우저로 더블클릭해서 열면 됩니다.

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소(repository)를 만듭니다. (예: `reports-page`)
2. 이 폴더의 파일들을 저장소에 업로드(또는 push)합니다.
   ```
   git init
   git add .
   git commit -m "활동 리포트 페이지"
   git branch -M main
   git remote add origin https://github.com/<사용자명>/<저장소명>.git
   git push -u origin main
   ```
3. 저장소 → **Settings → Pages** 로 이동합니다.
4. **Source** 를 `Deploy from a branch`, 브랜치를 `main` / 폴더를 `/ (root)` 로 설정하고 저장합니다.
5. 잠시 후 `https://<사용자명>.github.io/<저장소명>/` 에서 사이트가 열립니다.

## 내용 채우기

각 `.html` 파일을 열어 "여기에 ...적어 주세요" 부분을 실제 내용으로 바꾸면 됩니다.
