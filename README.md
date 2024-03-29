# 시작하며

이 글을 작성하게 된 계기는 누군가에게는 너무 당연한 일이지만 누군가에겐 어려운 일들이 많다는 것을 경험하게 되면서 이런 내용을 정리하면 좋겠다는 생각을 했습니다.

사소하지만 슬기롭게 회사 생활을 대처할 수 있을만한 내용들을 정리해서 공유하고 싶어서 이 문서를 작성하게 되었습니다.

처음에는 블로그나 사내 위키에만 작성해두려 했으나 GitHub을 통해 이 글을 작성하는 만큼, 이후에는 많은 분들이 참여해서 일 잘하는 방법들에 대해서 공유해줄 수 있으면 좋겠다는 기대를 합니다.

언제든 컨트리뷰트는 환영합니다! :D

# 일하기 스킬

## 슬랙 또는 메신저

- 전체 채널 파악하기
  - 파악한 뒤, 중요도에 따라 알림 설정을 해두면 좋다
- DM보다는 공개된 채널에서 대화하여 히스토리 남기기
  - 히스토리가 복잡한 경우에는 문서로 남겨두기
- 두괄식 소통
  - 본론을 먼저, 설명을 뒤로
  - 설명을 자세히 하려다가 시간을 소모하기보다 적당한 선에서 설명을 마치고 이해가 어렵다면 바로 온 콜을 요청하는 식으로 진행하면 좋다
  - 무엇을 해야 하는 지 / 발생한 건에 대한 설명 / 해결하기 위한 방법은 어떤 것들이 있는지를 간단하게 설명하여 요청한다
    - 설명할 수 있는 문서나 관련 링크가 있다면 포함한다
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
  - 질문에는 다음과 같은 내용들을 포함시킨다
    - 답변 응답 중요도 설정하기 (긴급, 천천히 알려줘도 되는 것 등)
    - 내가 알아봤던 방법
    - 내가 시도 했던 방법
    - 질문으로 원하는 결과
- 다른 사람들이 또 헤메지 않도록 문서화 하기

# 개발 스킬

## Git 잘 사용하기

- 커밋 메세지에는 다음과 같은 메세지가 담기는 것이 좋다
    - 현재 상황에 대한 설명
    - 왜 문제인지 설명
    - 코드 변경점이 해당 문제를 해결하는 방법을 설명
    - 변경점을 이해하는 데 필요한 추가 문서들 (예: 대체 솔루션, 설계 문서 링크, 이슈 티켓 넘버 등)
- 커밋 스타일
    - 회사에서 권장하는 커밋 스타일 가이드가 있다면 그것을 최우선으로 하자
    - 특별한 코딩 컨벤션이 없다면
        - 커밋 제목은 50글자 이내로
        - 영문 사용시 첫 글자는 대문자로
        - 제목의 마지막에는 마침표를 사용하지 않고
        - 본문의 행은 72글자 이내로 
    - 커밋메세지로 깃의 유형을 분류하길 원한다면 다음과 같은 커밋 스타일을 참조하면 좋다
        - 커밋 제목의 말머리로 표현하는 [Conventional Commits](https://www.conventionalcommits.org/)
        - 커밋 제목에 이모지로 표현하는 [gitmoji](https://gitmoji.dev/)

## 코드 리뷰

- 코드 리뷰에 기대하는 것
    - 개인의 작업을 리뷰함으로 변경된 작업이 개인의 책임에서 조직 전체의 책임이 될 수 있도록 한다
    - 사내의 코딩 컨벤션이나 기술적 지식 및 새로운 기술 스택을 공유
    - 변경된 코드가 영향을 사이드 이펙트 검증
    - 코드 리뷰에 기대하는 바는 조직마다 다를 수 있다
- 코드 리뷰에 임하는 마음가짐
    - 코드와 나를 동일시 하지 않는다
        - 일정의 압박, 요구사항이나 레거시를 제대로 파악하지 못해서 잘못된 코드가 나올 수 있다
            - 이런 문제를 바로 잡기 위한 프로세스기에 자책하거나 코드를 숨기려 하지 않는다
        - 남에게 코드를 보여야 한다는게 처음엔 부끄럽게 느껴질 수 있지만 더 개선할 수 있는 기회로 생각하자
    - 코드에서 문제점을 찾아내고 더 좋은 코드를 제안하여 도움이 되어야 한다는 강박에서 벗어나자
        - 신입의 경우 자신이 잘 모르는데 코드 리뷰를 한다는게 부담스러워하는 경우가 많다
            - 코드 리뷰에서는 항상 기여를 해야만 하는 것은 아니다
            - 코드를 읽어보고 모르는 것이 있으면 물어보는 것도 코드 리뷰의 일부분이다
    - 독성 말투를 사용하지 않는다
        - 결국 사람이 하는 일이다
        - 자신의 생각과 다른 코드를 보더라도 공격적인 말투보다는 동로를 배려하는 말투로 코드 변경을 권해보자
    - 리뷰 요청자는 리뷰어가 리뷰에만 집중할 수 있도록 충분한 설명과 자료를 제공한다
        - 코드 리뷰는 리뷰어에게 많은 에너지를 소모하게 하는 행위이므로 온전히 리뷰에 집중 할 수 있도록 하면 좋다
        - 리뷰 요청 전에 스스로 한번 더 리뷰를 해보면서 코드를 정리하자
        - 주제와 상관없는 커밋은 되도록 포함시키지 않는다
            - 필요하다면 커밋 / 브랜치를 나눠서 관심사를 분리시키는 것도 좋다
        - 설계 문서, 티켓 이슈, 파악한 내용, 변경하고자 한 내용, 작업하면서 고민했던 것을 자세히 작성하자
            - 팀 내에 코드 리뷰를 위한 [템플릿](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository)을 설정해두면 좋다
    - 리뷰어가 리뷰를 남겼을 때는 최대한 빠르게 응답하자
        - 리뷰를 해준 동료도 본인의 업무가 있기 때문에 오랫동안 코드 리뷰에 대한 내용을 기억하기는 어렵다
        - 최대한 빠르게 논의하여 코드를 개선하거나, 설명하면 좋다
- 코드 리뷰의 방식
    - 비동기로 코드 리뷰를 위한 온라인 플랫폼(GitHub / GitLab / Upsource 등)에서 진행하는 방법
        - 비동기로 요청하되 리뷰 희망 완료 일자를 명시하여 리뷰가 작업 일정 내에 마칠 수 있도록 관리해야 한다
        - 동료가 요청한 리뷰를 최대한 미루지 않고 하기 위해 노력해야한다 
    - 일부 팀원이 시간을 내서 모여서 코드 리뷰를 하는 방법
        - 변경 내용이 크거나 사이드 이펙트를 발생시키는 경우 혹은 중요도가 높은 작업에 대해서는 비동기 리뷰보다는 일정을 잡고 모여서 리뷰를 하는 편이 빠를 수 있다
- 코드 리뷰도 개발의 일부분이고 업무의 일환이다
    - 코드 리뷰를 하다가 개발을 못했다가 아니라 리뷰 또한 개발의 일부분이다
