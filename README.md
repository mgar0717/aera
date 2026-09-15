# aera

피아니스트 프로필 · 경력 · 공연 포스터 · 입시반주 홍보용 홈페이지.

빌드 도구 없이 `index.html` 하나로 구성된 정적 사이트 (casio, dbic 레포와 동일한 방식). GitHub Pages로 바로 배포합니다.

## 배포 (GitHub Pages)

1. 저장소 **Settings → Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / `/(root)`
4. 저장하면 `https://mgar0717.github.io/aera/` 에서 확인 가능

## 내용 채우기

`index.html`을 열어 대괄호 `[ ]`로 표시된 부분을 실제 내용으로 바꾸면 됩니다.

- `[한 줄 소개]` — 상단 히어로 영역
- 프로필 사진: GitHub 웹에서 `images/profile.jpg` 경로로 파일을 올리면 히어로/프로필 두 곳에 자동으로 뜸 (Add file → Upload files, 폴더명까지 `images/profile.jpg`로 지정)
- 프로필: 학력/약력 텍스트
- 경력: `<li>` 항목 복사해서 연도별로 추가/수정
- 포스터: 이미지 파일을 `posters/` 폴더에 올리면 됨 (GitHub 웹 Add file → Upload files, `posters/` 안으로). 올린 뒤 `index.html`의 `.poster-card` 텍스트를 `<img src="posters/파일명.jpg" alt="...">` 로 교체
- 입시반주: 서비스 소개 문구, 대상/방식 태그
- 문의: 전화(0507-1304-8709), 이메일(armg0717@gmail.com), 위치는 이미 반영됨

## 구조

- `index.html` — 페이지 전체 (HTML + CSS + JS, 별도 파일 없음)
- `posters/` — 연주 포스터 이미지 (필요 시 생성)
