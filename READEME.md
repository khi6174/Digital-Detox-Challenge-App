# Digital Detox Challenge App

스마트폰 과다 사용 문제를 해결하고, 사용자가 더 건강한 디지털 습관을 형성할 수 있도록 돕는 **안드로이드 기반 디지털 디톡스 챌린지 앱**입니다.

이 앱은 단순히 사용 시간을 줄이는 것을 넘어서,  
**앱 사용 제한**, **사용 시간 통계 시각화**, **챌린지 시스템**, **레벨업**, **커뮤니티 기능**을 통해  
사용자가 디지털 환경과 오프라인 생활의 균형을 찾을 수 있도록 설계되었습니다.

---

## Project Overview

현대 사회에서 스마트폰은 필수적인 도구가 되었지만, 과도한 사용은 불안, 우울, 집중력 저하, 생산성 감소, 수면 질 저하와 같은 문제를 유발할 수 있습니다.  
본 프로젝트는 이러한 문제의식에서 출발하여, 사용자가 자신의 스마트폰 사용 패턴을 인식하고 스스로 조절할 수 있도록 돕는 디지털 디톡스 앱을 구현하는 것을 목표로 했습니다. :contentReference[oaicite:1]{index=1}

---

## Key Features

### 1. App Blocking
사용자가 챌린지 시작 시 선택한 앱을 일정 시간 동안 실행하지 못하도록 제한합니다.

- Accessibility Service 기반 구현
- 특정 앱 실행 감지 후 홈 화면으로 강제 이동
- 챌린지 진행 중 디지털 사용 억제

### 2. Usage Time Tracking
스마트폰 사용 시간을 수집하고 시각화하여 사용 패턴을 직관적으로 확인할 수 있습니다.

- `UsageStatsManager`를 활용한 앱 사용 통계 조회
- 권한 확인 및 설정 페이지 이동 처리
- 차트 기반 시각화 기능 제공

### 3. Digital Detox Challenge
사용자가 스스로 디지털 디톡스 목표를 설정하고 도전할 수 있습니다.

- 챌린지 선택
- 제한 앱 설정
- 진행 시간 관리
- 완료 후 결과 확인

### 4. Level-Up System
챌린지 완료 결과를 바탕으로 사용자 레벨이 상승합니다.

- 챌린지 성공 여부 반영
- 진행 시간 기반 레벨 계산
- 성취감 제공을 통한 지속 사용 유도

### 5. User Authentication
Firebase 기반 사용자 인증 기능을 제공합니다.

- 회원가입
- 로그인 / 로그아웃
- 사용자 데이터 저장 및 관리

### 6. Community
사용자들이 경험과 후기를 공유할 수 있는 커뮤니티 기능을 제공합니다.

- 게시글 작성
- 리뷰 작성
- 본인 게시글 수정 / 삭제

---

## Tech Stack

### Mobile
- Android
- Java
- Android Studio

### Data / Backend
- Firebase Authentication
- Firebase Database

### Visualization
- MPAndroidChart

### Android System APIs
- Accessibility Service
- UsageStatsManager

---

## Project Structure

주요 화면 구성

- Splash Screen
- Login / Signup
- Main Screen
- Challenge Selection
- Challenge Progress
- Challenge Completion
- My Info
- Community

---

## Team Roles

팀명: 이건뭐조

- **김용우 (팀장)**
  - 전체 코드 총괄
  - 앱 접근성 기능 구현
  - 앱 사용 시간 통계 기능 구현
  - UI 개발 및 오류 수정

- **최영찬**
  - 앱 사용 시간 분석
  - 챌린지 진행 관리 및 UI

- **한민주**
  - 회원가입 / 로그인 / 로그아웃
  - 레벨업 시스템 구현

- **조준희**
  - 커뮤니티 기능 구현

- **임수정**
  - Firebase 연동

보고서 기준으로 프로젝트는 초기 UI 기획부터 기능 구현, 멘토 피드백 반영, 통합 테스트와 오류 수정 단계를 거쳐 완성되었습니다. :contentReference[oaicite:2]{index=2}

---

## Outcomes

이 프로젝트를 통해 다음과 같은 기능을 실제로 구현했습니다.

- 챌린지 진행 중 선택 앱 접근 차단
- 사용 시간 통계 수집 및 차트 시각화
- Firebase 기반 사용자 인증 및 데이터 저장
- 커뮤니티 게시글 관리
- 레벨업 시스템 적용

또한 이 앱은 사용자의 습관 개선, 디지털 웰빙 향상, 기업 및 교육기관의 활용 가능성까지 고려한 프로젝트로 기획되었습니다. :contentReference[oaicite:3]{index=3}

---

## Expected Impact

- 스마트폰 과다 사용 문제 완화
- 건강한 디지털 습관 형성 지원
- 스트레스 감소 및 오프라인 활동 참여 유도
- 디지털 웰빙 관리 도구로의 확장 가능성

---

## Future Improvements

- AI 기반 사용자 패턴 분석
- 개인 맞춤형 디톡스 추천 기능
- 통계 리포트 고도화
- 보상 및 게임화 시스템 강화

---

## License

This project is intended for educational and capstone design purposes.
