# 짝사랑은 교칙 위반인가요? — DOHUN SIDE

텍스트만 사용하는 도훈 시점의 선택형 미연시입니다. 외부 라이브러리와 이미지가 필요하지 않습니다.

## 실행
`index.html`을 브라우저에서 열면 됩니다.

## GitHub Pages 배포
1. GitHub에서 새 공개 저장소를 만듭니다.
2. `index.html`을 저장소 최상위에 업로드하고 커밋합니다.
3. Settings → Pages → Build and deployment에서 Deploy from a branch를 선택합니다.
4. Branch를 `main`, 폴더를 `/(root)`로 지정하고 Save를 누릅니다.
5. 배포가 완료되면 Pages에 표시되는 사이트 주소를 엽니다.

## 규칙
- 시작 호감도 50%, 0~100% 범위
- 총 10개 장면, 장면마다 3개 선택지
- 선택지 변화량은 +10 / +5 / -10 (5점 단위)
- 100: Happy / 50~99: Normal / 25~49: Bad 1 / 0~24: Bad 2
- 진행 상황은 브라우저 localStorage에 자동 저장

## 수정
`index.html` 안의 `scenes` 배열에서 대사와 선택지를, `endings` 객체에서 엔딩을 변경할 수 있습니다.
