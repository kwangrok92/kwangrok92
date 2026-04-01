<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1628,100:1e3a5f&height=220&section=header&text=Kwangrok%20Kim&fontSize=42&fontAlign=50&fontColor=f7f7f7&desc=iOS%20Developer%20%7C%204%2B%20Years&descSize=18&descAlign=50&descAlignY=75&fontAlignY=45" />
</p>

<p align="center">
  <b>Swift, RxSwift, ReactorKit 기반 대규모 상용 iOS 앱 개발자</b><br/>
  Clean Architecture 설계 · 지도 기반 O2O 서비스 · 웹-네이티브 통합
</p>

<br/>

## About Me

캐시워크에서 **4년간** 대규모 iOS 앱을 설계하고 개발해왔습니다.
4,000+ 기여, 140K+ 라인의 코드를 작성하며 건강관리 앱의 핵심 기능부터 위치 기반
리워드 서비스, 보물상자/캐시로또 시스템 개편까지 다양한 도메인을 경험했습니다.

<br/>

## Career

**Cashwalk Inc.** | iOS Developer | 2022.10 ~ Present

### Cashwalk (2025.08 ~ Present)

만보기 기반 리워드 플랫폼 앱. 동네산책, 혜택 탭, 홈/공통 모듈 담당.

| Module | Period | Description | Scale |
|--------|--------|-------------|-------|
| **Advantage (보물상자/캐시로또)** | 2026.03 ~ Present | 혜택 탭 보물상자 전면 개편 및 캐시로또 신규 탑재 | 227 files · +7,098 lines 배포 |
| **TownWalk** | 2025.08 ~ Present | 위치 기반 O2O 리워드 서비스, 영수증 리워드 MVP | 50+ PRs · 탐색 지도 + 영수증 인증 |
| **Home / Common** | 2025.10 ~ Present | 푸시 시스템 리팩토링, 코드 품질 표준화, 인증 보안 강화 | 415 files refactored |

### Geniet (2022.10 ~ 2025.12)

건강관리 앱. 만보기, 캐시로또, 웹뷰 브릿지 등 핵심 기능 개발.

| Scale |
|-------|
| 3,560 commits · 106K+ lines · 9,199 files |

### CashHomeTraining (2024.02 ~ 2025.07)

홈트레이닝 앱. SwiftUI + TCA 기반 카메라/음성 안내 모듈 개발.

| Scale |
|-------|
| 395 commits · SPM 기반 독립 모듈 |

<br/>

## Highlights

<table>
<tr>
<td width="50%" valign="top">

### Architecture & Design
- Clean Architecture + ReactorKit 기반 **167개 파일** 모듈 설계
- 과도한 추상화 제거로 **432줄 코드 삭제**, 실용적 아키텍처 수립
- SwiftUI + TCA 전환 주도, SPM 기반 독립 모듈 구조 구축

</td>
<td width="50%" valign="top">

### Large-Scale Feature Delivery
- 보물상자 개편 1차 배포: **227개 파일**, 20+ PR 체계적 분리 관리
- 캐시로또 모듈 신규 탑재 (+1,600 lines), 딥링크/푸시 통합
- 영수증 리워드 MVP 독립 설계 및 구현 (+4,400 lines, 184 files)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Map & Location
- NMapsMap 기반 탐색용 지도 시스템 (18가지 마커 상태 관리)
- Stack 기반 장소 이동 히스토리 관리
- 반경 기반 실시간 마커 상태 동기화

</td>
<td width="50%" valign="top">

### System Refactoring
- 푸시 시스템 재설계: 30+ 타입 지원하는 확장 가능한 구조
- SwiftLint 경고 **415개 파일** 일괄 정리, 빌드 경고 0 달성
- 웹뷰-네이티브 **20+ 브릿지 함수** 시스템 구축

</td>
</tr>
</table>

<br/>

## Tech Stack

<p align="center">

**Language & Framework**

<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/UIKit-000000?style=flat-square&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white"/>

**Architecture & Reactive**

<img src="https://img.shields.io/badge/ReactorKit-0E83CD?style=flat-square"/> <img src="https://img.shields.io/badge/RxSwift-B7178C?style=flat-square"/> <img src="https://img.shields.io/badge/TCA-000000?style=flat-square"/> <img src="https://img.shields.io/badge/Clean%20Architecture-4CAF50?style=flat-square"/>

**UI & Tools**

<img src="https://img.shields.io/badge/SnapKit-2C8EBB?style=flat-square"/> <img src="https://img.shields.io/badge/Lottie-00DDB3?style=flat-square"/> <img src="https://img.shields.io/badge/NMapsMap-03C75A?style=flat-square&logo=naver&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/Tuist-5C2D91?style=flat-square"/> <img src="https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black"/>

</p>

<br/>

## Problem Solving

> **"문제를 구조적으로 분석하고, 확장 가능한 해결책을 설계합니다."**

| Challenge | Approach | Result |
|-----------|----------|--------|
| 보물상자 오픈 플로우 자정 경계값 오류 | 기기 시간 대신 서버 시간 기반 비교로 전환 | Race Condition 방어, 안정적 날짜 전환 |
| 227개 파일 규모 보물상자 개편 | 오픈 플로우 → 튜토리얼 → API → 배포로 PR 분리 | 20+ PR 체계적 관리, 1차 배포 완료 |
| GPS 기반 18가지 UI 상태 동기화 | ReactorKit 상태 머신 + 반경 기반 마커 관리 | 안정적인 실시간 지도 서비스 |
| 하드코딩된 푸시 분기 로직 | FCMMessageType enum 기반 아키텍처 재설계 | 30+ 타입 확장 가능한 구조 |
| 수천 개의 SwiftLint 경고 누적 | 규칙별 분류 후 자동+수동 일괄 수정 | 415개 파일 정리, 빌드 경고 0 |
| Clean Architecture 과도한 추상화 | 불필요한 UseCase 레이어 제거, Repository 직접 호출 | 432줄 삭제, 생산성 향상 |

## Connect

<p align="center">
  <a href="mailto:kwangrok92@naver.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://crazydeer.tistory.com/"><img src="https://img.shields.io/badge/Blog-000000?style=for-the-badge&logo=blogger&logoColor=white"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/kwangrok-kim"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>
