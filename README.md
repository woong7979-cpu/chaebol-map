# 재벌 지도 2026 (한국어판) — 공개용

공정거래위원회 기업집단포털 공식 자료로 만든 정적 웹사이트입니다. 서버·DB 없이 파일만 올리면 됩니다.

## 구성
- index.html : 사이트 전체 (쉽게 배우기 · 관계도 · 지분도 원본 · 계열사 · 용어사전 · 데이터)
- charts/1.webp ~ 102.webp : 공정위 소유지분도 원본 이미지
- og-ko.png : 링크 공유 미리보기 이미지
- vercel.json : 이미지 캐시 설정

## Vercel에 올리는 방법 (코딩 없이)
1. github.com 로그인 → New repository → 이름(예: chaebol-map) → Create
2. "uploading an existing file" 클릭 → 이 폴더 안의 파일·폴더를 전부 끌어다 놓기 → Commit
3. vercel.com 로그인(GitHub 계정으로) → Add New → Project → 방금 만든 저장소 Import
4. Framework Preset: Other, 나머지 기본값 → Deploy
5. 배포 주소(예: https://chaebol-map.vercel.app)가 나오면 index.html의 og:image 값을
   https://배포주소/og-ko.png 로 바꿔 다시 Commit (링크드인 미리보기용)

## 출처와 고지
- 공정거래위원회 「2026년 기업집단별 소유지분도」, 기업집단포털(egroup.go.kr) 소속회사 개요·주주 현황·지주회사 자·손자회사 현황(2026.5 지정 기준)
- 재무는 2025 회계연도 별도(개별) 재무제표 기준
- 본 자료는 참고용으로 세부적인 정보는 'egroup.go.kr' 기업집단포털에서 재확인 부탁드립니다.
