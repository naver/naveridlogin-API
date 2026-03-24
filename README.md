# 네이버로그인 API 문의

네이버로그인(네아로) 연동 과정에서 발생한 **기술 문의**와 **오류 신고**를 이 저장소의 Discussion 을 통해 접수받고 있습니다.

> [!IMPORTANT]
> 이슈 등록 시 **Client Secret은 절대 입력하지 마세요.** Client ID만 입력해 주세요.

---

## 문의하기

아래 표를 참고하여 상황에 맞는 템플릿으로 이슈를 등록해 주세요.

| 상황 | 템플릿 |
|---|---|
| 일반 문의 | [💬 일반 문의](../../issues/new?template=03-general.yml) |

---

## FAQ

문의 전에 아래 내용을 먼저 확인해 주세요.

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

[개발자센터 홈](https://developers.naver.com/products/login/api/api.md) 페이지를 확인해 주세요.

</details>

<details>
<summary><strong>로그인 버튼 디자인을 임의로 변경해도 되나요?</strong></summary>

임의 변경은 불가합니다. 색상, 로고, 형태는 공식 [브랜드 가이드라인](https://developers.naver.com/docs/login/bi/bi.md)을 준수해야 하며, 크기 조정 정도만 허용됩니다. 미준수 시 검수 반려 또는 이용 중지될 수 있습니다.

</details>

<details>
<summary><strong>서비스 URL이 변경되었을 때 어떻게 수정하나요?</strong></summary>

개발자센터 → 내 애플리케이션 → API 설정 탭에서 직접 수정 가능합니다. 도메인 자체 변경 시 재검수가 필요할 수 있으며, redirect_uri 파라미터도 함께 업데이트해야 합니다.

</details>

</details>
<summary><strong>콜백 URL을 여러 개 등록할 수 있나요?</strong></summary>

여러 개 등록 가능합니다. 단, 로그인 요청 시 redirect_uri는 등록된 URL과 정확히 일치해야 합니다.

</details>

</details>
<summary><strong>해외 서비스에도 네이버 로그인을 적용할 수 있나요?</strong></summary>

적용 가능합니다. 다양한 글로벌 서비스도 실제 적용 중입니다. 단, 이용자의 정보가 해외의 서버로 전송된다면, 반드시 '국외이전동의' 설정을 해주셔야 합니다. 
- 애플리케이션 -> API설정 ->개인정보 국외이전 동의 ->국외이전 정보 등록

</details>

</details>
<summary><strong>앱 이름이나 로고가 변경되면 재심사가 필요한가요?</strong></summary>

네, 재검수가 필요합니다. 앱 이름과 로고는 사용자의 네이버 로그인 동의 화면에 노출되는 정보이기 때문에, 변경 시 반드시 검수를 다시 받아야 합니다.
 - 변경 절차: 개발자센터 → 내 애플리케이션 → 앱 이름/로고 수정 → 파트너센터를 통해 재검수 요청
앱 이름은 실제 서비스명과 일치해야 하며, 로고는 서비스에서 사용 중인 공식 이미지를 사용해야 합니다. 검수 완료 전까지는 기존 정보로 서비스가 유지됩니다.
</details>


---

## 참고 문서

| 문서 | 설명 |
|---|---|
| [적용 가이드](https://developers.naver.com/products/login/userguide/) | 네이버로그인 신청부터 적용까지 전체 흐름 안내 |
| [개발 가이드](https://developers.naver.com/docs/login/devguide/) | API 스펙, 파라미터, 응답값 등 개발 상세 가이드 |
| [검수 가이드](https://developers.naver.com/docs/login/verify/) | 검수 신청 전 필수 확인 사항 안내 |
| [문의폼](https://help.naver.com/support/alias/naveridlogin/naveridlogin_03.naver) | 등록자 아이디 변경 등 이슈 외 문의 |
