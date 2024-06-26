# 서드파티 쿠키

## 등장 배경

- 개인화된 정보 제공을 위해
- 맞춤 광고 추적

## 지원 중단 발표

- 구글이 서드파티 쿠키를 지원 중단한다고 발표함
- 엄격해진 개인정보 보호 정책

```text
2024년 1월부터 Chrome에서 서드 파티 쿠키가 지원 중단됩니다. 
지원 중단 절차는 2024년 1분기에 1% 테스트로 시작되며 2024년 말까지 서드 파티 쿠키를 완전히 지원 중단할 계획입니다.
삽입 사용자 세션을 설정하기 위해 서드 파티 쿠키에 대한 Looker의 종속 항목으로 인해 삽입 사용 사례에 영향을 미칠 수 있습니다.
Looker 인스턴스에 커스텀 도메인을 설정하지 않고 쿠키 없는 삽입을 사용하지 않는 모든 삽입 고객은 조치를 취해야 합니다.
```

## 퍼스트파티 쿠키, 서드파티 쿠키

| 1st | 3rd |
| --- | --- |
| 내가 웹사이트에 직접 생성한 쿠키 | 제 3자가 웹사이트에 생성한 쿠키 |
| 자동 로그인, 장바구니 | 광고 최적화 |

## 서드파티 쿠키 생성 과정

- [에드센스 테스트](https://milise.tistory.com/71)
- [stackoverflow](https://stackoverflow.com/)
- [zendesk](https://zendesk.co.kr)

1. 사용자가 <www.A.com> 방문
2. <www.A.com> 에서 <www.B.com>를 위한 쿠키 생성 (서드 파티 쿠키)
3. 나는 <www.B.com을> 방문한적이 없지만, 해당 페이지 접속 시 저장된 쿠키가 이용됨 (개인화된 컨텐츠 제공)
