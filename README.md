# 시작하며

이 글을 작성하게 된 계기는 누군가에게는 너무 당연한 일이지만 누군가에겐 어려운 일들이 많다는 것을 경험하면서이다.

사소하지만 슬기롭게 회사 생활을 대처할 수 있을만한 내용들을 정리해서 공유하고 싶어서 이 문서를 작성하게 되었다.

GitHub을 통해 이 글을 작성하는 만큼, 이후에는 많은 분들이 참여해서 잘 일하는 방법들에 대해서 공유해줄 수 있으면 좋겠다는 기대도 있다.

언제든 컨트리뷰트는 환영한다.


# 일하기 스킬

## 슬랙 또는 메신저

- 전체 채널 파악하기
  - 파악한 뒤, 중요도에 따라 알림 설정을 해두면 좋다
- 두괄식 소통
  - 본론을 먼저, 설명을 뒤로
  - 설명을 자세히 하려다가 시간을 소모하기보다 적당한 선에서 설명을 마치고 이해가 어렵다면 바로 온 콜을 요청하는 식으로 진행하면 좋다
  - 무엇을 해야 하는 지 / 발생한 건에 대한 설명 / 해결하기 위한 방법은 어떤 것들이 있는지를 간단하게 설명하여 요청한다. 설명할 수 있는 문서나 관련 링크가 있다면 포함한다
- 비동기식 대화
  - `자리에 계신가요?` / `안녕하세요?` 와 같은 인사와 함께 답변을 기다리지 않고 바로 본론을 말한다
    - 물론 업무가 아닌 간단한 대화를 위해서라면 동기식 대화가 더 좋다
  - 비동기 소통을 위한 메신저이지만 무작정 답변을 미루지 않는다
    - 당장 답장하기 어렵다면 확인 후 답변을 하겠다고 예상 답변 기간을 안내해주도록 하자
  - 비동기 대화를 믿고 필요한게 있으면 즉시 스레드를 남기자
    - 늦었다고 내일 보내야지 하다보면 까먹기 마련이다. 되도록 생각났을 때 바로 커뮤니케이션 하자
    - 만약 늦은 시간이 부담스럽다면 예약 발송 기능이 있는지 확인해보자
- 업무 메신저도 이메일 커뮤니케이션과 비슷하다. 참조를 활용한다
  - 커뮤니케이션 때 놓치지 않도록 업무 연관자를 함께 멘션한다
- DM보다는 공개된 채널에서 대화하여 히스토리 남기기
  - 히스토리가 복잡한 경우에는 문서로 남겨두기

## 문서화

- 사내에서 사용하는 문서화 도구를 잘 파악하기
- 위키의 경우 문서를 따라하다가 잘 되지 않는 경우 직접 갱신한다
  - 문서에 오너십이 있는 경우 멘션을 하여 문서를 따라했을 때 발생한 문제를 공유하고 업데이트하도록 알려준다

## 질문 잘하기

- 무작정 질문하지 않고 알아보기
  - 사내 문서 탐색
  - 외부 검색
  - 30분 ~ 1시간 정도 검색해봐도 안나오는 경우, 업무가 빨리 진행되야 한다면 멈추고 질문을 한다
- 질문하기
  - 질문에는 다음과 같은 내용들을 포함시킨다.
    - 답변 응답 중요도 설정하기 (긴급, 천천히 알려줘도 되는 것 등)
    - 내가 알아봤던 방법
    - 내가 시도 했던 방법
    - 질문으로 원하는 결과
- 다른 사람들이 또 헤메지 않도록 문서화 하기

# 개발 스킬

## Git 잘 사용하기

- 커밋 메세지에는 다음과 같은 메세지가 담기는 것이 좋다.
    - 현재 상황에 대한 설명
    - 왜 문제인지 설명
    - 코드 변경점이 해당 문제를 해결하는 방법을 설명
    - 변경점을 이해하는 데 필요한 추가 문서들 (예: 대체 솔루션, 설계 문서 링크, 이슈 티켓 넘버 등)
- 커밋 스타일
    - 회사에서 권장하는 커밋 스타일 가이드가 있다면 그것을 최우선으로 하자.
    - 특별한 코딩 컨벤션이 없다면
        - 커밋 제목은 50글자 이내로
        - 영문 사용시 첫 글자는 대문자로
        - 제목의 마지막에는 마침표를 사용하지 않고
        - 본문의 행은 72글자 이내로 
    - 커밋메세지로 깃의 유형을 분류하길 원한다면 다음과 같은 커밋 스타일을 참조하면 좋다
        - 커밋 제목의 말머리로 표현하는 [Conventional Commits](https://www.conventionalcommits.org/)
        - 커밋 제목에 이모지로 표현하는 [gitmoji](https://gitmoji.dev/)
