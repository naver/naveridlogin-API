# 네이버로그인 API 문의

네이버로그인(네아로) 연동 과정에서 발생한 **기술 문의**와 **오류 신고**를 이 저장소의 이슈(Issues)를 통해 접수받고 있습니다.

> [!IMPORTANT]
> 이슈 등록 시 **Client Secret은 절대 입력하지 마세요.** Client ID만 입력해 주세요.

---

## 문의하기

아래 표를 참고하여 상황에 맞는 템플릿으로 이슈를 등록해 주세요.

| 상황 | 템플릿 |
|---|---|
| REST API 설정(redirect_uri, scope 등) 관련 궁금한 점이 있을 때 | [🔧 기술 문의 - REST API 설정](../../issues/new?template=01-technical-rest-api.yml) |
| 네이버로그인을 적용했는데 정상 동작하지 않을 때 | [🚨 기술 문의 - 동작 오류](../../issues/new?template=02-technical-not-working.yml) |
| 그 외 일반 문의 | [💬 일반 문의](../../issues/new?template=03-general.yml) |

---

## FAQ

문의 전에 아래 내용을 먼저 확인해 주세요.

<details>
<summary><strong>네이버로그인 뱃지가 노출되지 않아요.</strong></summary>

아래 두 가지를 확인해 주세요.

1. 개발자센터에 등록한 **서비스 URL**이 광고나 사이트 검색에 노출되는 URL과 동일한지 확인해 주세요.
2. 서비스에 **일정 수준 이상의 사용자**가 발생하고 있는지 확인해 주세요.

</details>

<details>
<summary><strong>"서비스 설정에 오류가 있다"는 메시지가 노출돼요.</strong></summary>

[네이버 도움말](https://help.naver.com/support/alias/naveridlogin/naveridlogin_02.naver)을 참고해 주세요.

</details>

<details>
<summary><strong>등록자 아이디를 변경해야 해요.</strong></summary>

이슈 등록이 아닌 [문의폼](https://help.naver.com/support/alias/naveridlogin/naveridlogin_03.naver)으로 접수해 주세요.

</details>

<details>
<summary><strong>영문 가이드가 필요해요.</strong></summary>

dl_naverid@navercorp.com 으로 문의해 주세요.

</details>

---

## 참고 문서

| 문서 | 설명 |
|---|---|
| [적용 가이드](https://developers.naver.com/products/login/userguide/) | 네이버로그인 신청부터 적용까지 전체 흐름 안내 |
| [개발 가이드](https://developers.naver.com/docs/login/devguide/) | API 스펙, 파라미터, 응답값 등 개발 상세 가이드 |
| [검수 가이드](https://developers.naver.com/docs/login/verify/) | 검수 신청 전 필수 확인 사항 안내 |
| [문의폼](https://help.naver.com/support/alias/naveridlogin/naveridlogin_03.naver) | 등록자 아이디 변경 등 이슈 외 문의 |
