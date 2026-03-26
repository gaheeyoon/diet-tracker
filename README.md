# 가히의 다이어트 트래커

매일 식단·운동·체중을 간편하게 기록하는 웹앱입니다.

## GitHub Pages 배포 방법

1. GitHub에서 새 레포지토리 생성 (예: `diet-tracker`)
2. `index.html` 파일을 레포지토리에 업로드
3. Settings > Pages > Branch: main / (root) 선택 후 Save
4. 배포 URL: `https://{username}.github.io/diet-tracker/`

## Google Sheets 연동 방법

1. Google Sheets 새 파일 생성
2. 상단 메뉴 > 확장프로그램 > Apps Script
3. 앱 내 **설정 탭**의 코드를 복사해서 붙여넣기
4. 저장(Ctrl+S) 후 배포 > **웹앱으로 배포**
   - 설명: 다이어트 트래커
   - 다음 사용자로 실행: **나**
   - 액세스 권한: **모든 사람**
5. 배포 URL 복사 → 앱 설정 탭에 붙여넣기 후 저장

## 기능

- ✅ 오늘 기록: 체중 / 식단 4끼 체크 / 운동·물 체크 / 수면시간 / 메모
- 📊 기록 확인: 체중 그래프 / 식단·운동 준수율 / 날짜별 상세보기
- 🥗 식단표: PT 선생님이 짜준 식단 항상 확인 가능
- ☁️ Google Sheets 자동 동기화 (선생님 공유용)
