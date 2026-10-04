# 구원해주소서

이미지 없는 Hero → Story → Characters → Play Guide → Begin 순서의 반응형 랜딩페이지입니다.
제목은 Noto Serif KR, 본문은 Noto Sans KR을 사용합니다.

## 에셋 추가
1. GitHub의 `assets/` 폴더에 사진을 업로드합니다.
2. `assets-data.js`의 배열에 항목을 추가합니다.
```js
window.ASSETS = [
  { title: '남주 · 일상', src: 'assets/male-daily.png' },
  { title: '여주 · 일상', src: 'assets/female-daily.png' }
];
```
에셋 페이지에서 원본 이미지를 새 탭으로 열 수 있습니다. 업로드 전에는 준비 중 안내가 표시됩니다.

## GitHub Pages
저장소 Settings → Pages → Deploy from a branch → main / (root) → Save.
플레이 공개 링크는 확정된 후 index.html의 마지막 화면에 추가하세요.
명령어 화면은 설명용 출력 예시이며 실제 AI 실행 기능은 아닙니다.
