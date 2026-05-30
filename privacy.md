# 개인정보 처리방침 (Privacy Policy)

**시행일: 2026-05-29**

Ibou AI(이하 "회사")는 ibouBudget 앱(이하 "앱") 이용자의 개인정보를 중요하게 생각하며, 「개인정보 보호법」(PIPA), GDPR, Apple App Store 정책을 준수합니다. 본 방침은 한국어를 정본으로 합니다.

---

## 1. 처리 원칙: 로컬 우선

ibouBudget은 **사용자의 가계부 데이터(거래 내역, 카테고리, 예산, 자산, 프로필 등)를 사용자의 기기에서만 저장·처리**합니다. 별도 회원가입이 없으며, 회사 서버에는 개인 데이터를 전송하지 않습니다.

- **로컬 저장**: SwiftData(기기 내 데이터베이스)에 저장
- **iCloud 동기화**(선택): 사용자가 iCloud Drive를 활성화한 경우 Apple의 iCloud에 암호화되어 동기화되며, 회사는 접근할 수 없습니다
- **회사 서버 전송 없음**: 거래 내역, 금액, 카테고리, 이름, 생년월일, 성별 등은 회사 서버로 전송되지 않습니다
- **선택적 AI 기능은 예외**: 아래 3·4항의 AI 기능을 사용할 때에 한해, 처리에 필요한 데이터가 **Google(Gemini)** 등 외부 AI 서비스로 전송될 수 있습니다. 사용하지 않으면 전송되지 않습니다.

## 2. 처리하는 정보

| 항목 | 처리 위치 | 목적 |
|---|---|---|
| 거래 내역 (금액, 메모, 카테고리, 날짜) | 기기 내부 | 가계부 기능 |
| 사용자 프로필 (이름, 성별, 생년월일) — 선택 입력 | 기기 내부 | 온디바이스 상품 추천 그룹화 (예: "30대 여성"), 외부 전송 없음 |
| 영수증 사진 (무료 스캔) | 기기 내부 (Apple Vision OCR 온디바이스) | OCR 처리, 외부 전송 없음 |
| 영수증 사진 (AI 정밀 스캔, Pro/체험) | **Google(Gemini) 클라우드로 전송** | 정밀 OCR 처리. 아래 4항 참조 |
| AI 입력·분석 텍스트 (자연어 입력·AI 상담·월간 회고·카테고리 추천) | 지원 기기는 온디바이스, 그 외 **Google(Gemini) 클라우드** | 텍스트 이해·생성. 아래 3·4항 참조 |
| 위치 정보 | 기기 내부 | 오늘의 날씨 무드 (open-meteo.com 호출 시 위/경도만 사용, 식별자 없음). 지오펜스는 기기 내 처리 |
| 기기 식별자 / 광고 ID | **수집 안 함** | — |
| 결제 정보 | Apple StoreKit | 회사는 카드 정보 등에 접근하지 않습니다 |

## 3. AI 기능과 데이터 전송 (중요)

본 앱의 AI 기능은 두 가지 경로로 동작합니다.

- **온디바이스(Apple FoundationModels / Apple Intelligence)**: 지원 기기(iOS 26+ 및 호환 하드웨어)에서는 자연어 입력·AI 상담 등이 **기기 안에서** 처리되어 외부로 전송되지 않습니다.
- **클라우드(Google Gemini, Firebase AI Logic 경유)**: 온디바이스를 지원하지 않는 기기이거나, 클라우드 처리가 필요한 기능(영수증 AI 정밀 스캔, 월간 회고 생성 등)에서는 처리에 필요한 데이터가 **Google로 전송**됩니다.
  - 전송될 수 있는 데이터: **영수증 이미지**, 또는 **거래 요약 텍스트(금액·분류·메모)와 사용자가 입력한 문장**
  - 전송 목적: 해당 AI 결과 생성에 한함. 전송된 데이터는 Google의 개인정보처리방침에 따라 처리됩니다 (https://policies.google.com/privacy).
  - 이 데이터는 사용자 신원(이름·계정)과 연결되지 않으며, 추적·광고 목적으로 사용되지 않습니다.
- AI 기능은 **선택 사항**이며, 사용하지 않으면 위 전송은 발생하지 않습니다.

## 4. 외부 서비스

| 서비스 | 목적 | 전송 데이터 |
|---|---|---|
| Apple StoreKit | Pro 구독 결제 | Apple이 직접 처리 (회사 미관여) |
| Apple Vision | 무료 영수증 OCR | 기기에서만 처리, 외부 전송 없음 |
| Apple FoundationModels (Apple Intelligence) | 자연어·AI 상담 등 (지원 기기) | 기기에서만 처리 (iOS 26+) |
| **Google Gemini (Firebase AI Logic)** | 영수증 AI 정밀 스캔, 자연어/상담 클라우드 폴백, 월간 회고·카테고리 추천 | **영수증 이미지** 또는 **거래 요약 텍스트·입력 문장** (신원 비연결) |
| open-meteo.com | 오늘의 날씨 무드 | 위/경도 (식별자 없음) |
| Yahoo Finance / CoinGecko | 자산 가격 조회 (사용자가 자산 추적 기능 사용 시) | 종목 코드 (식별자 없음) |
| Firebase App Check | 앱 무결성 검증 | 익명 디바이스 토큰 |

## 5. 14세 미만 이용자

「개인정보 보호법」 관련 규정에 따라 14세 미만 이용자의 개인정보 처리에는 법정대리인 동의가 필요합니다. 본 앱은 프로필 입력 단계에서 14세 미만으로 판별되면 입력을 차단합니다. 차단되더라도 앱의 가계부 기능은 그대로 이용할 수 있습니다.

## 6. 처리 위탁

AI 기능 사용 시 처리에 필요한 데이터가 다음 수탁자에게 위탁 처리됩니다.

| 수탁자 | 위탁업무 | 위탁시점 |
|---|---|---|
| Google LLC (Gemini, Firebase AI Logic) | AI 영수증 정밀 스캔, 자연어/상담 클라우드 폴백, 월간 회고·카테고리 추천 결과 생성 | 해당 AI 기능 사용 시 |
| Google LLC (Firebase App Check) | 앱 무결성 검증 토큰 발급 | 앱 실행 시 |

수탁자는 위탁받은 업무 목적 외 이용이 금지됩니다.

## 7. 개인정보의 국외 이전

위 수탁 처리 중 일부는 국외로 이전됩니다.

- **이전받는 자**: Google LLC
- **이전되는 국가**: 미국
- **이전 일시 및 방법**: AI 기능 사용 시점, HTTPS 암호화 전송
- **이전 항목**: 영수증 이미지 또는 거래 요약 텍스트·입력 문장 (신원 비연결), 앱 무결성 토큰
- **이전 목적**: 본 방침 3·4·6항에 기재된 AI 결과 생성 및 무결성 검증
- **보유·이용 기간**: Google의 개인정보처리방침에 따름 (https://policies.google.com/privacy)

이용자는 AI 기능을 사용하지 않음으로써 위 국외 이전을 거부할 수 있습니다.

## 8. 보관 및 파기

기기 내 데이터는 사용자가 앱을 삭제하면 함께 삭제됩니다. 회사는 별도 사본을 보유하지 않습니다. AI 기능을 통해 Google로 전송된 데이터의 보관은 Google의 정책을 따릅니다.

## 9. 이용자 권리

이용자는 언제든 다음 권리를 행사할 수 있습니다.

- 개인정보 **열람·정정·삭제** 요구 (앱 내에서 직접 가능)
- 개인정보 **처리정지** 및 **동의 철회** 요구 (iCloud 동기화 끄기, AI 기능 미사용, 앱 삭제로 즉시 효력)
- **자동화된 결정에 대한 권리**: AI 기능이 산출한 결과(추천 카테고리, 회고, 상담 응답 등)에 대해 **설명을 요구**하거나 **이의를 제기**할 수 있습니다. 본 앱의 AI 결과는 정보 제공·참고용이며 사용자 권리·의무에 직접적 효력을 미치지 않습니다.

권리 행사는 support@ibou.ai 로 요청하시거나 앱 내 기능을 통해 직접 처리하실 수 있습니다.

## 10. 개인정보 보호책임자

- **개인정보 보호책임자**: Ibou AI 운영팀
- **연락처**: support@ibou.ai

## 11. 문의

개인정보 관련 문의: **support@ibou.ai**

## 12. 개정

본 방침은 법령 또는 서비스 변경에 따라 개정될 수 있습니다. 중요한 변경 시 앱 내 공지로 사전 안내합니다.

---

# Privacy Policy (English)

**Effective: 2026-05-29**

ibouBudget is local-first: your budgeting data (transactions, categories, budgets, assets, profile) is stored and processed **on your device**. There is no account sign-up, and the company does not transmit personal data to its own servers.

- All financial records, categories, profile (name/gender/birthdate), and receipt images are stored locally via SwiftData.
- Optional iCloud sync uses Apple's encrypted iCloud Drive; the company has no access.
- Location is used only at point-of-call to fetch weather mood from open-meteo.com (latitude/longitude only, no identifier); geofencing is processed on-device.
- No advertising IDs or device fingerprints are collected.
- Children under 14 are blocked from profile entry per Korean PIPA (guardian-consent requirement). The rest of the app remains usable without a profile.

**AI features and data transmission (important).** AI features run either **on-device** (Apple FoundationModels / Apple Intelligence on supported hardware, iOS 26+) or in the **cloud via Google Gemini (through Firebase AI Logic)**. When the cloud path is used — e.g., AI receipt OCR, or natural-language/chat/recap on unsupported devices — the data needed to produce the result is sent to Google:

- Data that may be sent: **receipt images**, or **transaction summary text (amounts, categories, memos) and your typed input**.
- Purpose: solely to generate the AI result. Sent data is handled under Google's Privacy Policy (https://policies.google.com/privacy). It is not linked to your identity and is not used for tracking or advertising.
- AI features are **optional**; if you don't use them, no such transmission occurs.

| Third party | Purpose | Data sent |
|---|---|---|
| Apple StoreKit | Pro subscription billing | Handled by Apple |
| Apple Vision | Free receipt OCR | On-device only |
| Apple FoundationModels | Natural language / chat (supported devices) | On-device only |
| Google Gemini (Firebase AI Logic) | AI receipt OCR, cloud fallback for NL/chat, recap & category suggestions | Receipt image or transaction summary text / typed input (not linked to identity) |
| open-meteo.com | Weather mood | Latitude/longitude (no identifier) |
| Yahoo Finance / CoinGecko | Asset prices (if asset tracking used) | Ticker symbols (no identifier) |
| Firebase App Check | App integrity | Anonymous device token |

**Processing entrustment & cross-border transfer.** When AI features are used, the data required is entrusted to Google LLC (Gemini via Firebase AI Logic) and transferred to the United States over HTTPS. Items transferred: receipt image, or transaction summary text / typed input (not linked to identity); app integrity token. Retention follows Google's Privacy Policy. You can decline the transfer by not using AI features.

**User rights.** You may request access, correction, deletion, suspension of processing, and withdrawal of consent. For automated outputs (category suggestions, recaps, chat responses), you may request an explanation or object — these outputs are informational and do not produce legal or significant effects.

**Data Protection Officer**
- Officer: Ibou AI Operations Team
- Contact: **support@ibou.ai**

Questions: **support@ibou.ai**
