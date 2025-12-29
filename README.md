# 🏐 골볼 데이터 뷰어 Ver5

골볼 경기의 데이터를 분석하고 시각화하는 웹 기반 도구입니다.

## ✨ 주요 기능

- 📊 **데이터 시각화**: 투구 궤적, 히트맵, 시간별 이벤트 그래프
- 🎯 **고급 분석**: 포지션 시퀀스, 투구 패턴 TOP 15, 골 이벤트 분석
- 🔍 **다양한 필터**: 팀, 선수, 포지션, 기술, 이벤트별 필터링
- 💾 **데이터 관리**: JSON/CSV 파일 불러오기 및 내보내기
- 📧 **이메일 발송**: 분석 결과를 이메일로 전송

## 🚀 시작하기

### 1. 뷰어 열기
`index.html` 파일을 웹 브라우저에서 엽니다.

### 2. 데이터 불러오기
- "파일 선택" 버튼을 클릭하여 JSON 또는 CSV 파일을 선택합니다
- 샘플 데이터는 `sample_data.json` 파일을 사용해보세요

### 3. 데이터 분석
- 자동으로 생성되는 시각화를 확인합니다
- 필터를 사용하여 원하는 데이터만 분석할 수 있습니다

## 📚 문서

- **[사용자 매뉴얼](USER_MANUAL.md)**: 상세한 기능 설명과 사용 방법
- **[스크린샷 가이드](SCREENSHOT_GUIDE.md)**: 매뉴얼용 스크린샷 촬영 가이드

## 📁 파일 구조

```
GOALBALL_VIEWER/
├── index.html              # 메인 뷰어 파일
├── sample_data.json        # 샘플 데이터 파일
├── README.md              # 프로젝트 소개
├── USER_MANUAL.md         # 사용자 매뉴얼
├── SCREENSHOT_GUIDE.md    # 스크린샷 가이드
├── screenshots/           # 매뉴얼용 스크린샷 폴더
├── history/               # 이전 버전
│   └── goalball_Viewer_ver5_new.html
└── LICENSE
```

## 💻 시스템 요구사항

### 권장 브라우저
- Google Chrome (최신 버전)
- Microsoft Edge (최신 버전)
- Mozilla Firefox (최신 버전)

### 최소 요구사항
- 화면 해상도: 1280 × 720 이상
- JavaScript 활성화 필수

## 🎯 데이터 형식

### JSON 형식
```json
{
  "matchDate": "2025-01-15",
  "matchName": "샘플 경기",
  "teamA": "한국팀",
  "teamB": "일본팀",
  "records": [
    {
      "team": "A",
      "player": 1,
      "position": "L",
      "skill": "F",
      "event": "G",
      "course": [...]
    }
  ]
}
```

### CSV 형식
첫 번째 행에 헤더가 포함되어야 합니다:
```
ID,시간,팀,선수,포지션,시간대,기술,이벤트,이벤트2,패턴,경기시간,이동X,이동Y,...
```

## 🛠️ 개발 정보

### 버전
- **현재 버전**: Ver5
- **마지막 업데이트**: 2025년

### 기술 스택
- HTML5
- CSS3 (Gradient Animations)
- Vanilla JavaScript
- Canvas API

## 📝 라이센스

이 프로젝트는 라이센스 파일을 참조하세요.

## 🤝 기여

개선 사항이나 버그 리포트는 언제든 환영합니다!

## 📞 문의

사용 중 문제가 발생하거나 기능 개선 요청이 있으시면 개발팀에 문의해 주세요.

---

**© 2025 Goalball Data Viewer. All rights reserved.**
