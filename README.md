<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1628,100:1e3a5f&height=220&section=header&text=Kwangrok%20Kim&fontSize=42&fontAlign=50&fontColor=f7f7f7&desc=iOS%20Developer%20%7C%204%2B%20Years&descSize=18&descAlign=50&descAlignY=75&fontAlignY=45" />
</p>

<p align="center">
  <b>상용 iOS 앱 개발 · 개인 앱 기획부터 출시까지</b><br/>
  Swift · SwiftUI · ReactorKit / TCA · Clean Architecture · 웹-네이티브 하이브리드
</p>

<br/>

## About Me

캐시워크에서 **4년간** 대규모 iOS 앱을 설계·개발하며 4,000+ 기여, 140K+ 라인을 작성했습니다.
회사에서는 수백만 사용자가 쓰는 앱의 안정성과 확장 가능한 구조를 다루고,
개인 프로젝트에서는 **기획 → 설계 → 구현 → 배포**까지 혼자 진행하며,
[**타이머핏**](https://apps.apple.com/kr/app/id6792751925)과 [**공모아**](https://apps.apple.com/kr/app/id6793987876) **두 개의 앱을 App Store에 직접 출시**했고, 세 번째 앱 **Doblin**이 심사 중입니다.

<br/>

## Career

**Cashwalk Inc.** · iOS Developer · 2022.10 ~ Present

| Project | Period | Role | Scale |
|---------|--------|------|-------|
| **Cashwalk** | 2025.08 ~ Present | 혜택 탭 보물상자 전면 개편 · 캐시로또 신규 탑재 · 위치 기반 O2O 리워드(동네산책) · 홈/공통 모듈 | 227 files 배포 · 50+ PRs · 415 files 리팩터링 |
| **Geniet** | 2022.10 ~ 2025.12 | 건강관리 앱 — 만보기, 캐시로또, 웹뷰 브릿지 등 핵심 기능 | 3,560 commits · 106K+ lines |
| **CashHomeTraining** | 2024.02 ~ 2025.07 | 홈트레이닝 앱 — SwiftUI + TCA 기반 카메라/음성 안내 모듈 | 395 commits · SPM 독립 모듈 |

**Key Achievements**

- Clean Architecture + ReactorKit 기반 **167개 파일** 모듈 설계, 과도한 추상화 제거로 **432줄 삭제**
- 227개 파일 규모 개편을 **오픈 플로우 → 튜토리얼 → API → 배포**로 20+ PR 분리해 안전하게 배포
- NMapsMap 기반 **18가지 마커 상태 머신** + 반경 기반 실시간 동기화로 GPS 리워드 서비스 구현
- 하드코딩된 푸시 분기를 `FCMMessageType` enum 아키텍처로 재설계 — **30+ 타입 확장 가능 구조**
- SwiftLint 경고를 **415개 파일** 일괄 정리해 빌드 경고 0 달성, 웹뷰-네이티브 **20+ 브릿지** 구축

<br/>

## Personal Projects

> 회사에서 검증한 구조를 개인 앱에서 다시 실험합니다.
> UIKit/RxSwift → SwiftUI/TCA → React + Capacitor 하이브리드까지, 스택을 직접 골라 끝까지 만들어 봅니다.

| Project | Period | Stack | Scale | Status |
|---------|--------|-------|-------|--------|
| **TimerFit** | 2025.04 ~ Present | SwiftUI · Combine · watchOS | 194 commits · 53 PRs · 6.2K lines | 🚀 [**App Store 출시**](https://apps.apple.com/kr/app/id6792751925) |
| **Gongmoa** (공모아) | 2026.07 ~ Present | React · TypeScript · Capacitor · Supabase | 60 commits · 26 PRs · 7.8K lines | 🚀 [**App Store 출시**](https://apps.apple.com/kr/app/id6793987876) |
| **Doblin** | 2026.07 ~ Present | SwiftUI · TCA · SwiftData | 52 commits · 4.7K lines · 5개 언어 | 🔍 App Store 심사 중 |
| **Cargineer** | 2025.04 ~ 2025.06 | UIKit · ReactorKit · RxSwift · CoreData | 40 commits · CI 파이프라인 구축 | 아카이브 |

<table>
<tr>
<td width="50%" valign="top">

### ⏱ TimerFit — 인터벌 서킷 타이머 <sub>App Store 출시</sub>

<a href="https://apps.apple.com/kr/app/id6792751925"><img src="https://img.shields.io/badge/App%20Store-%ED%83%80%EC%9D%B4%EB%A8%B8%ED%95%8F-0D96F6?style=flat-square&logo=appstore&logoColor=white"/></a>

심플한 카운트다운 타이머에서 시작해 **라운드마다 다른 운동을 따라 하는 인터벌 서킷 타이머**로 확장한 iOS 앱. **기획부터 심사·출시까지 혼자 진행해 App Store에 정식 출시**했습니다.

- 서킷 구간/라운드를 순차 진행하는 **상태 머신**(`IntervalTimerService`) 직접 설계
- **MVVM + Service 프로토콜 추상화**, 외부 의존성 0 · UserDefaults(Codable) 저장
- 타바타/HIIT/EMOM 프리셋 + **사용자 서킷·커스텀 운동 생성/편집**
- 플랫폼 중립 레이어(`TimerFitShared`)로 분리해 **watchOS 워치 앱 확장** — 아이폰-워치 루틴 동기화
- **fastlane + GitHub Actions**로 아카이브 → TestFlight → 심사 제출 자동화
- App Store 4.2(최소 기능) 대응을 위해 제품 범위를 재설계 후 재제출 → **v1.0.0 출시**, 워치 앱을 담은 **v1.1.0 업데이트 배포**

</td>
<td width="50%" valign="top">

### 📈 Gongmoa (공모아) — 공모주 청약 관리 <sub>App Store 출시</sub>

<a href="https://apps.apple.com/kr/app/id6793987876"><img src="https://img.shields.io/badge/App%20Store-%EA%B3%B5%EB%AA%A8%EC%95%84-0D96F6?style=flat-square&logo=appstore&logoColor=white"/></a> <a href="https://gongmoa.app"><img src="https://img.shields.io/badge/Web-gongmoa.app-1e3a5f?style=flat-square&logo=googlechrome&logoColor=white"/></a>

헤비 공모주 비례 투자자를 위한 **청약 일정·기록·손익 자동 계산** 앱. 스프레드시트 수기 관리를 대체하며, **첫 커밋부터 App Store 출시까지 1주**에 완주했습니다.

- **웹 코어 하이브리드** — React + TS 코어를 Capacitor로 iOS 네이티브 셸에 탑재
- 같은 코어를 웹([gongmoa.app](https://gongmoa.app))으로도 배포 — **웹·iOS 동시 서비스**
- 파생 상태를 저장하지 않는 **단일 진실 원본** 설계 (손익·자금효율 항상 재계산)
- **오프라인 우선** — Repository 추상화로 SQLite(iOS)/IndexedDB(웹) 저장, 로그인 없이도 완전 동작
- **다기기 동기화** — Supabase Realtime · **RLS** 정책 · Edge Function 계정 삭제
- **Xcode Cloud CI** — 웹 코어 빌드를 네이티브 빌드 단계에 주입해 자동화
- 도메인 계산 로직 우선 테스트(Vitest), 모든 기능을 **PR 단위**로 분리 관리

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧌 Doblin — 성장형 할 일 앱 <sub>App Store 심사 중</sub>

"오늘 지금 뭘 해야 하지?"에 답하는 할 일 앱. 완료할수록 자라는 캐릭터가 보상입니다. 현재 **v1.0.0 App Store 심사 진행 중**입니다.

- **TCA + SwiftData** — 단일 진실 원본, `TestStore` 기반 유닛 테스트
- 사용자 데이터가 생기기 전에 **SwiftData 스키마 버저닝** 선반영
- **자연어 날짜 파싱** 입력, 반복 작업(매일/주중/주간/월간), 홈 화면 **위젯**(App Group 공유)
- 로컬 알림(전역 + 작업별), 드래그 정렬 · 스와이프 · 실행 취소 토스트
- **5개 언어** 현지화 + 인앱 언어 전환, 다크 우선 테마, 접근성 패스
- **XcodeGen** 프로젝트 생성 · 재현 가능한 스크린샷 파이프라인 · **fastlane**으로 메타데이터/스크린샷 업로드까지 자동화

</td>
<td width="50%" valign="top">

### 🚗 Cargineer — 차량 관리

정비 기록·주유 내역·연비를 한 번에 관리하는 다중 차량 관리 앱.

- **UIKit + ReactorKit + RxSwift** 단방향 데이터 흐름 구성
- **CoreData** 로컬 영속화, 메인 차량 중심 대시보드 UI
- `NotificationManager` 추상화 — 로컬 푸시 등록/수신, 포그라운드 Alert 대체 처리
- 알림 탭 → 탭 전환 딥링크 연결, 등록/실패 시 햅틱 피드백
- **GitHub Actions CI** 구축 — 시뮬레이터·OS 버전 명시로 빌드 안정화
- `main` / `develop` / `feature` 브랜치 전략과 PR 리뷰 흐름 연습

</td>
</tr>
</table>

<br/>

## Tech Stack

<p align="center">

**Language & Framework**

<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/UIKit-000000?style=flat-square&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/watchOS-000000?style=flat-square&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>

**Architecture & State**

<img src="https://img.shields.io/badge/ReactorKit-0E83CD?style=flat-square"/> <img src="https://img.shields.io/badge/RxSwift-B7178C?style=flat-square"/> <img src="https://img.shields.io/badge/TCA-000000?style=flat-square"/> <img src="https://img.shields.io/badge/Combine-FF2D55?style=flat-square"/> <img src="https://img.shields.io/badge/Clean%20Architecture-4CAF50?style=flat-square"/> <img src="https://img.shields.io/badge/Zustand-433E38?style=flat-square"/>

**Data & Backend**

<img src="https://img.shields.io/badge/SwiftData-0071E3?style=flat-square&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/CoreData-147EFB?style=flat-square&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>

**UI & Tooling**

<img src="https://img.shields.io/badge/SnapKit-2C8EBB?style=flat-square"/> <img src="https://img.shields.io/badge/Lottie-00DDB3?style=flat-square"/> <img src="https://img.shields.io/badge/NMapsMap-03C75A?style=flat-square&logo=naver&logoColor=white"/> <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white"/> <img src="https://img.shields.io/badge/Tuist-5C2D91?style=flat-square"/> <img src="https://img.shields.io/badge/XcodeGen-1575F9?style=flat-square"/> <img src="https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

</p>

<br/>

## How I Work

> **"문제를 구조적으로 분석하고, 확장 가능한 해결책을 설계합니다."**

| Challenge | Approach | Result |
|-----------|----------|--------|
| 227개 파일 규모 기능 개편 | 오픈 플로우 → 튜토리얼 → API → 배포로 PR 분리 | 20+ PR 체계적 관리, 1차 배포 완료 |
| 보물상자 자정 경계값 오류 | 기기 시간 대신 서버 시간 기준 비교로 전환 | Race Condition 방어, 안정적 날짜 전환 |
| Clean Architecture 과도한 추상화 | 불필요한 UseCase 레이어 제거, Repository 직접 호출 | 432줄 삭제, 생산성 향상 |
| 개인 앱의 반복되는 배포 작업 | fastlane lane + GitHub Actions로 아카이브~심사 자동화 | 빌드마다 수동 작업 제거 |

<br/>

## Connect

<p align="center">
  <a href="mailto:kwangrok92@naver.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://crazydeer.tistory.com/"><img src="https://img.shields.io/badge/Blog-000000?style=for-the-badge&logo=blogger&logoColor=white"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/kwangrok-kim"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>
