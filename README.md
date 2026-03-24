# 🚗 차량 관리 일지 앱

싼타페 더 프라임 · 쏘울 차량 정비 기록 관리 PWA

## 배포 방법 (GitHub Pages)

### 1단계 — GitHub 저장소 만들기
1. https://github.com 에서 로그인
2. 우측 상단 **+** → **New repository** 클릭
3. Repository name: `car-app` 입력
4. **Public** 선택
5. **Create repository** 클릭

### 2단계 — 파일 업로드
1. 저장소 화면에서 **uploading an existing file** 클릭
2. 이 폴더의 모든 파일 드래그 앤 드롭:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` 폴더 전체
3. **Commit changes** 클릭

### 3단계 — GitHub Pages 활성화
1. 저장소 상단 **Settings** 탭 클릭
2. 왼쪽 메뉴 **Pages** 클릭
3. Branch: **main** 선택 → **Save**
4. 1~2분 후 주소 생성됨: `https://[내 아이디].github.io/car-app`

### 4단계 — 폰에 설치하기

**안드로이드 (크롬)**
1. 위 주소를 크롬으로 열기
2. 주소창 오른쪽 점 3개 → **홈 화면에 추가**
3. 앱처럼 설치 완료!

**아이폰 (사파리)**
1. 위 주소를 사파리로 열기
2. 하단 공유 버튼 → **홈 화면에 추가**
3. 앱처럼 설치 완료!

## 기능
- ✅ 싼타페 / 쏘울 탭 전환
- ✅ 기록 추가 / 삭제
- ✅ 검색 & 연도 필터
- ✅ 연도별 지출 차트
- ✅ 영구 저장 (localStorage)
- ✅ 오프라인 사용 가능 (Service Worker)
- ✅ 모바일 앱 설치 (PWA)
