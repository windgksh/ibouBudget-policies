# 개인정보 처리방침 (Privacy Policy)

**시행일: 2026-05-27**

ibou(이하 "회사")는 ibouBudget 앱(이하 "앱") 이용자의 개인정보를 중요하게 생각하며, 「개인정보 보호법」(PIPA), GDPR, Apple App Store 정책을 준수합니다. 본 방침은 한국어를 정본으로 합니다.

---

## 1. 처리 원칙: 로컬 우선

ibouBudget은 **사용자의 가계부 데이터(거래 내역, 카테고리, 예산, 자산, 프로필 등)를 사용자의 기기에서만 저장·처리**합니다. 별도 회원가입이 없으며, 회사 서버에는 개인 데이터를 전송하지 않습니다.

- **로컬 저장**: SwiftData(기기 내 데이터베이스)에 저장
- **iCloud 동기화**(선택): 사용자가 iCloud Drive를 활성화한 경우 Apple의 iCloud에 암호화되어 동기화되며, 회사는 접근할 수 없습니다
- **회사 서버 전송 없음**: 거래 내역, 금액, 카테고리, 이름, 생년월일, 성별 등은 회사 서버로 전송되지 않습니다

## 2. 처리하는 정보

| 항목 | 처리 위치 | 목적 |
|---|---|---|
| 거래 내역 (금액, 메모, 카테고리, 날짜) | 기기 내부 | 가계부 기능 |
| 사용자 프로필 (이름, 성별, 생년월일) — 선택 입력 | 기기 내부 | 온디바이스 상품 추천 그룹화 (예: "30대 여성"), 외부 전송 없음 |
| 영수증 사진 | 기기 내부 (Apple Vision OCR 온디바이스) | OCR 처리 후 즉시 폐기 |
| 위치 정보 | 기기 내부 | 오늘의 날씨 무드 (open-meteo.com 호출 시 위/경도만 사용, 식별자 없음) |
| 기기 식별자 / 광고 ID | **수집 안 함** | — |
| 결제 정보 | Apple StoreKit | 회사는 카드 정보 등에 접근하지 않습니다 |

## 3. 14세 미만 이용자

「개인정보 보호법」 §22-2에 따라 14세 미만 이용자의 개인정보 처리에는 법정대리인 동의가 필요합니다. 본 앱은 프로필 입력 단계에서 14세 미만으로 판별되면 입력을 차단합니다.

## 4. 외부 서비스

| 서비스 | 목적 | 전송 데이터 |
|---|---|---|
| Apple StoreKit | Pro 구독 결제 | Apple이 직접 처리 (회사 미관여) |
| Apple Vision | 영수증 OCR | 기기에서만 처리, 외부 전송 없음 |
| Apple Intelligence / FoundationModels | 카테고리 자동 분류, 상품 추천 | 기기에서만 처리 (iOS 26+) |
| open-meteo.com | 오늘의 날씨 무드 | 위/경도 (식별자 없음) |
| Yahoo Finance / CoinGecko | 자산 가격 조회 (사용자가 자산 추적 기능 사용 시) | 종목 코드 (식별자 없음) |
| Firebase App Check | 앱 무결성 검증 | 익명 디바이스 토큰 |

## 5. 보관 및 파기

기기 내 데이터는 사용자가 앱을 삭제하면 함께 삭제됩니다. 회사는 별도 사본을 보유하지 않습니다.

## 6. 이용자 권리

이용자는 언제든 다음을 할 수 있습니다:
- 앱 내에서 데이터 열람·수정·삭제
- iCloud 동기화 비활성화
- 앱 삭제로 모든 데이터 폐기

## 7. 문의

개인정보 관련 문의: **support@ibou.ai**

## 8. 개정

본 방침은 법령 또는 서비스 변경에 따라 개정될 수 있습니다. 중요한 변경 시 앱 내 공지로 사전 안내합니다.

---

# Privacy Policy (English)

**Effective: 2026-05-27**

ibouBudget processes user data exclusively on the user's device. The company does not collect, transmit, or store personal data on its servers.

- All financial records, categories, profile (name/gender/birthdate), and receipt images are stored locally via SwiftData.
- Optional iCloud sync uses Apple's encrypted iCloud Drive; the company has no access.
- Location is used only at point-of-call to fetch weather mood from open-meteo.com (latitude/longitude only, no identifier).
- No advertising IDs or device fingerprints are collected.
- Children under 14 are blocked from profile entry per Korean PIPA §22-2.

Questions: **support@ibou.ai**
