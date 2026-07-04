# 여우방 맞팔확인 V11.5 GOLD ULTIMATE

## 구성
- index.html
- manifest.json
- icon.svg
- room-list.csv
- config.json
- README.md
- .nojekyll

## 수정 내용
- GitHub 로컬 room-list.csv 우선 로딩
- Google Sheets 자동연동 실패 시 저장 캐시 사용
- 관리자 로그인 완전 재작성
- Enter 키 로그인 지원
- 관리자 CSV 파일 명단 저장 기능 추가
- 명단 붙여넣기 저장 기능 유지
- 전체 명단 검색/복사/인스타 링크 유지

## 중요
room-list.csv는 GitHub에 같이 업로드하는 백업 명단 파일입니다.
현재 파일은 기본 양식이므로, 실제 명단 CSV로 교체하면 Google Sheets가 실패해도 앱이 0명으로 뜨지 않습니다.
