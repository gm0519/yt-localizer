# YT Localizer

YouTube 영상 제목·설명글을 다국어로 자동 번역해서 YouTube에 한 번에 등록하는 도구.

---

## 사용 전 준비

### 1. Gemini API Key
- https://aistudio.google.com 접속
- [Get API key] → [Create API key] 클릭
- 키 복사 (`AIzaSy...`)

### 2. YouTube OAuth Client ID
- https://console.cloud.google.com 접속 (채널 소유자 계정)
- 새 프로젝트 생성
- YouTube Data API v3 활성화
- OAuth 동의 화면 설정 (외부 / 테스트 상태 유지)
- 테스트 사용자에 본인 이메일 추가
- 사용자 인증 정보 → OAuth 클라이언트 ID 생성 (웹 애플리케이션)
- 승인된 JavaScript 원본 추가:
  - `http://localhost`
  - `https://gm0519.github.io`
- 승인된 리디렉션 URI 추가:
  - `https://gm0519.github.io/yt-localizer/`
- Client ID 복사 (`123456...apps.googleusercontent.com`)

---

## 사용 방법

1. https://gm0519.github.io/yt-localizer 접속
2. Gemini API Key, YouTube Client ID 입력
3. Google 계정으로 로그인
4. 번역할 영상 선택
5. 언어 선택 (기본 50개국 추천 선택됨)
6. 번역 시작
7. 결과 확인 후 자동 등록

---

## 참고

- API 키는 브라우저 localStorage에만 저장 (외부 전송 없음)
- Gemini 무료 티어: 하루 약 25개 영상 번역 가능 / 매일 오후 4시 리셋 (한국 시간)
- YouTube OAuth는 7일마다 재로그인 필요 (테스트 앱 상태)
- 한글만 번역, 영어 원문은 그대로 유지
