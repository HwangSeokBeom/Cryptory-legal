# Cryptory Legal & Support Pages

Cryptory 앱의 앱 심사 제출 및 공개 안내를 위한 정적 법률/지원 문서 세트입니다.

이 저장소는 순수 HTML/CSS 기반의 단일 정적 사이트로 구성됩니다. GitHub Pages에 그대로 배포하여 개인정보처리방침, 이용약관, 고객지원, 계정 삭제 안내, 투자 유의 및 면책 안내, 커뮤니티 운영 정책 URL로 사용할 수 있습니다.

> 중요: 본 문서는 운영용 초안입니다. 실제 배포, 앱 심사 제출, 서비스 운영 전에 반드시 법률 검토가 필요합니다.

## 레포 목적

Cryptory는 가상자산 시세 조회, 거래소별 비교, 자산 조회, 주문, 거래소 API 연동 기능을 제공하는 앱입니다. 이 저장소는 심사자와 이용자가 아래 정보를 빠르게 확인할 수 있도록 공개 문서 페이지를 제공합니다.

- 서비스 개요와 공식 문서 링크
- 개인정보 수집, 이용, 보관, 삭제 기준
- 서비스 이용약관
- 고객지원 및 문의 방법
- 계정 삭제 안내
- 투자 유의 및 외부 거래소 연동 관련 면책
- 커뮤니티 사용자 생성 콘텐츠, 신고, 차단, 콘텐츠 조치 운영 기준

## 포함 문서 목록

- `index.html`: Cryptory Legal & Support 허브 페이지
- `privacy.html`: 개인정보처리방침 초안
- `terms.html`: 서비스 이용약관 초안
- `support.html`: 고객지원 및 문의 안내
- `delete-account.html`: 계정 삭제 및 거래소 연결 해제 안내
- `disclaimer.html`: 투자 유의 및 면책 안내
- `community-policy.html`: 커뮤니티 운영 정책, 신고, 차단, 콘텐츠 검토 기준
- `styles.css`: 모든 HTML 문서의 공통 스타일
- `README.md`: 레포 목적, 배포 안내, placeholder 관리 문서

## GitHub Pages URL

이 저장소의 GitHub Pages 기준 URL은 다음과 같습니다.

- Homepage: `https://hwangseokbeom.github.io/Cryptory-legal/`
- Terms: `https://hwangseokbeom.github.io/Cryptory-legal/terms.html`
- Privacy Policy: `https://hwangseokbeom.github.io/Cryptory-legal/privacy.html`
- Support: `https://hwangseokbeom.github.io/Cryptory-legal/support.html`
- Delete Account: `https://hwangseokbeom.github.io/Cryptory-legal/delete-account.html`
- Disclaimer: `https://hwangseokbeom.github.io/Cryptory-legal/disclaimer.html`
- Community Policy: `https://hwangseokbeom.github.io/Cryptory-legal/community-policy.html`

## 앱 환경변수 링크 매핑

| Env | Page |
| --- | --- |
| APP_HOMEPAGE_URL | `/` |
| TERMS_URL | `/terms.html` |
| PRIVACY_POLICY_URL | `/privacy.html` |
| SUPPORT_URL | `/support.html` |
| ACCOUNT_DELETION_URL | `/delete-account.html` |
| INVESTMENT_DISCLAIMER_URL | `/disclaimer.html` |
| COMMUNITY_POLICY_URL | `/community-policy.html` |

## GitHub Pages 배포 방법

1. 저장소 루트에 현재 파일들이 모두 있는지 확인합니다.
2. GitHub 저장소의 `Settings` > `Pages`로 이동합니다.
3. `Build and deployment`에서 `Source`를 `Deploy from a branch`로 선택합니다.
4. 배포 브랜치를 선택하고 폴더는 `/ (root)`로 설정합니다.
5. 저장 후 GitHub Pages 주소가 생성될 때까지 기다립니다.
6. 생성된 공개 URL에서 모든 HTML 페이지가 열리는지 확인합니다.
7. 앱 심사 제출 전 placeholder를 실제 운영 정보로 교체합니다.

## 제출용 URL 예시

배포 기준 주소가 `[DEPLOY_BASE_URL]`인 경우 아래 URL을 제출할 수 있습니다.

- Product / Legal Hub URL: `[DEPLOY_BASE_URL]/`
- Privacy Policy URL: `[DEPLOY_BASE_URL]/privacy.html`
- Terms of Service URL: `[DEPLOY_BASE_URL]/terms.html`
- Support URL: `[DEPLOY_BASE_URL]/support.html`
- Delete Account URL: `[DEPLOY_BASE_URL]/delete-account.html`
- Disclaimer URL: `[DEPLOY_BASE_URL]/disclaimer.html`
- Community Policy URL: `[DEPLOY_BASE_URL]/community-policy.html`

프로젝트 저장소 방식의 GitHub Pages라면 예시는 다음과 같습니다.

- `https://<github-username>.github.io/Cryptory-legal/`
- `https://<github-username>.github.io/Cryptory-legal/privacy.html`
- `https://<github-username>.github.io/Cryptory-legal/terms.html`
- `https://<github-username>.github.io/Cryptory-legal/support.html`
- `https://<github-username>.github.io/Cryptory-legal/delete-account.html`
- `https://<github-username>.github.io/Cryptory-legal/disclaimer.html`
- `https://<github-username>.github.io/Cryptory-legal/community-policy.html`

사용자/조직 페이지 저장소라면 저장소명이 경로에 붙지 않을 수 있습니다.

## Placeholder 교체 목록

배포 전 아래 placeholder를 실제 값으로 교체해야 합니다.

- `[LEGAL_ENTITY_NAME]`: 운영 주체명 또는 법인명
- `[REPRESENTATIVE_NAME]`: 대표자명 또는 책임자명
- `[BUSINESS_ADDRESS]`: 사업장 주소 또는 운영 주소
- `[SUPPORT_EMAIL]`: 고객지원 이메일
- `[PRIVACY_EMAIL]`: 개인정보 문의 이메일
- `[EFFECTIVE_DATE]`: 문서 시행일
- `[LAST_UPDATED]`: 최종 업데이트일
- `[DEPLOY_BASE_URL]`: 배포 기준 URL
- `[APP_DELETE_ACCOUNT_PATH]`: 앱 내 계정 삭제 경로
- `[ACCOUNT_DELETION_PROCESSING_TIME]`: 계정 삭제 처리 기간
- `[API_STORAGE_DESCRIPTION]`: API Key, Secret, Access Token 저장 및 보호 방식
- `[SUPPORTED_EXCHANGES]`: 연동 지원 거래소 목록
- `[API_PERMISSION_SCOPE]`: 권장 또는 허용 API 권한 범위
- `[LOGIN_PROVIDERS]`: 로그인 제공자 목록
- `[INFRA_PROVIDERS]`: 서버, 클라우드, 분석, 크래시 리포팅 등 인프라 제공자
- `[DATA_RETENTION_PERIOD]`: 개인정보 및 로그 보관 기간
- `[RESPONSE_TIME_TARGET]`: 문의 응답 목표 기간
- `[GOVERNING_LAW]`: 준거법
- `[JURISDICTION]`: 관할
- `[MINOR_POLICY]`: 미성년자 이용 정책
- `[OPEN_SOURCE_PAGE_STATUS]`: 오픈소스 고지 페이지 운영 여부

## 배포 후 확인 체크리스트

- 모든 HTML 페이지가 공개 URL에서 정상적으로 열리는지 확인합니다.
- 상단 navigation의 Home, Privacy Policy, Terms, Support, Delete Account, Disclaimer, Community Policy 링크가 모두 동작하는지 확인합니다.
- 각 페이지 footer의 지원 이메일, 개인정보 문의 이메일, 최종 업데이트 날짜가 실제 값으로 교체되었는지 확인합니다.
- `privacy.html`에 실제 수집 항목, 보관 위치, 외부 서비스, 보관 기간이 정확히 반영되었는지 확인합니다.
- `delete-account.html`의 앱 내 탈퇴 경로가 실제 앱 화면과 일치하는지 확인합니다.
- `disclaimer.html`에 시세, 주문, 체결, 잔고 정보의 한계와 이용자 책임이 명확히 표시되었는지 확인합니다.
- `community-policy.html`에 신고, 차단, 콘텐츠 숨김/삭제, 운영자 검토 기준이 실제 앱 기능과 일치하는지 확인합니다.
- 앱 심사 제출 전 모든 placeholder가 남아 있지 않은지 확인합니다.
- 법률 검토 후 확정 문안으로 교체합니다.

## 문서 갱신 기준

다음 변경이 발생하면 관련 문서를 함께 갱신해야 합니다.

- 로그인 방식 또는 계정 체계 변경
- 거래소 연동 방식, 지원 거래소, API 권한 범위 변경
- API Key, Secret, Access Token 저장 또는 암호화 방식 변경
- 주문, 체결, 잔고, 거래 내역 처리 방식 변경
- 커뮤니티 기능, 신고/차단 기능, 콘텐츠 검토 또는 이용 제한 기준 변경
- 개인정보 수집 항목, 보관 기간, 파기 절차 변경
- 고객지원 채널, 처리 기간, 운영 주체 정보 변경
- 법령, 앱 심사 기준, 거래소 정책 변경

## 법률 검토 필요 고지

이 저장소의 문서는 Cryptory 서비스 운영을 돕기 위한 초안입니다. 실제 법적 효력, 규제 준수, 앱 심사 대응, 개인정보보호법 및 관련 법령 준수 여부는 보장하지 않습니다.

정식 배포 전에는 서비스 실제 동작, 데이터 흐름, 거래소 연동 범위, 운영 주체 정보, 관할 법령을 기준으로 법률 전문가의 검토를 받아야 합니다.
