# ZenDesk Support

## 1. ZenDesk를 사용하는 목적

---

현재 카페의 문의 내역을 실시간으로 확인하기 힘들며, 메일 답변을 보냈을 시 스팸 메일로 분류되는 상황

이러한 고객과의 소통을 더 원활하게 해줄 수 있는 **ZenDesk Support**를 활용하기로 회의에 건의

</br>

## 2. ZenDesk 사용방법

---

### **2-1) [티켓 구성](https://support.zendesk.com/hc/ko/articles/4408881925786)**

</br>

### **채널** (커뮤니케이션 목록)

---

- 이메일 보내기
- 회사 웹사이트에서 지원 요청 양식 작성
- 전화로 연락
- 문자 메시지를 통한 채팅
- ~~젠 데스크 서포트 포털에서 지원 요청 양식 작성~~
- ~~트윗 보내기~~
- ~~페이스북 담벼락에 게시~~

위의 채널들 중 고객과 연락할 수 있는 방법을 결정, 또한 현재 사용중인 Slack에 젠 데스크 계정을 추가하여 고객과 소통하는 더 많은 방법을 구현

모든 채널(젠 데스크에서 설정한 채널)에서 받는 모든 지원 요청이 **Zendesk Support Ticket** 으로 변환, 티켓은 이메일과 형식이 매우 유사

![Ticket1](https://support.zendesk.com/hc/article_attachments/4408894986266/ticket_anatomy_top.png)

![Ticket2](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/ticket_anatomy_main2.png)

</br>

### **댓글 영역**

---

- 공개 답장 : 해당 티켓을 보는 모든 사람이 볼 수 있도록 공개된다.

- 참조 필드 : 다른 외부 사용자를 답장의 참조 목록에 추가할 수 있다.

- 내부 메모 : 고객에게는 보이지 않고 내부 커뮤니케이션용으로 사용 가능하다.

- 매크로를 사용해 단일 표준 응답으로 답변할 수 있다.

</br>

### **티켓 사용자 유형**

---

- 모든 티켓에는 **요청자**(지원을 요청한 고객)의 이름이 포함되어 있다.

- 상담원이 티켓에 배정되면 **담당자**가 된다.

- 상담원이 고객 대신 티켓을 등록하면 해당 상담원은 **제출자**가 된다.

- 다른 내부 사용자를 상담원이 초대(참조)하면 이들은 **팔로워**가 된다.

</br>

### **티켓을 배정하는 방법**

---

- 티켓의 담당자 필드 옆의 아래쪽 화살표 클릭하여 본인의 이름을 선택하거나, 나에게 배정을 클릭

- 해당 티켓의 유형 및 우선 순위 필드를 설정할 수 있다. (초기 옵션 - 유형 : 문제, 우선 순위 : 보통)

- 위의 변경 내용을 저장하려면 신규로 제출 버튼을 클릭

- 티켓을 상담원에게 배정하면 해당 티켓이 자동으로 "등록"으로 설정된다.

</br>

### **티켓 수명 주기**

---

![Ticket3](https://zen-marketing-documentation.s3.amazonaws.com/docs/ko/gsg_submit_button.png)

- 신규 : 고객으로 부터 요청이 처음 도착

- 등록 : 상담원이 티켓에 배정

- 보류 : 상담원이 고객에게 후속 질문

- 해결 : 상담원이 문제를 해결

- 종료 : 특정 일수가 지난 티켓이며 참조할 수 있도록 보관(상담원이 티켓을 직접 종료로 제출할 수 없음)

- 해당 상담원의 답변을 고객이 만족하지 않는다면 **해결**된 티켓에 **재요청**이 가능하며 요청시 티켓은 재등록된다.

- 티켓의 수명별로 검색하여 모든 티켓을 빠르게 볼 수 있다.

- 고객이 받은 지원에 만족하는지 간단한 설문 조사를 보내도록 설정할 수 있다.

</br>

### **2-2) [티켓 및 사용자 구성](https://support.zendesk.com/hc/ko/articles/4408883609370)**

</br>

### **보기**

---

![View](https://zen-marketing-documentation.s3.amazonaws.com/docs/ko/gsg_unassigned_tickets_new_thumb.png)

보기는 티켓의 특성에 따라 티켓을 구성하므로 두 개 이상 티켓이 보기에 나타날 수 있다. 새 보기를 만들거나 필요에 맞게 기존의 보기를 수정할 수 있다.

![View2](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/gsg_view_available_for.png)

- 공유 보기 : Zendesk 계정에서 제공되는 미리 정의된 보기

- 제한 보기 : 특정 상담원 그룹만 볼 수 있는 보기(관리자만 설정 가능)
- 개인용 보기 : 본인만 액세스할 수 있는 보기(모든 상담원이 설정 가능)

</br>

### **나만의 보기 생성 방법**

---

- 보기 아이콘
![View3](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/views_icon.png)

- 보기 목록 아래의 **더 보기** 클릭 후 **보기 추가** 클릭

![View4](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_assignee.png)

- 제목 입력
  
- 티켓 : 담당자 / is / (현재 사용자) 또는 상담원 목록의 본인 이름 선택
  
- **위의 조건과 일치하는 항목 미리보기**를 클릭하면 정의한 조건의 결과를 바로 볼 수 있다.
  
- 보기를 정의할 때 서식과 해당 보기에 액세스할 수 있는 사람도 정의할 수 있다.
  
- 보기 만들기

</br>

### **그룹으로 상담원 및 티켓 세분화하기**

---

Zendesk Support에서는 상담원을 그룹으로 구성하며 티켓을 상담원에게 배정하면 그 상담원이 속한 그룹에도 배정된다. 그리고 상담원은 두 개 이상의 그룹에 속할 수 있다. 또한, 티켓을 그룹에만 배정하고 그룹 내 특정 상담원에게는 배정하지 않을 수도 있다.

- 관리자 아이콘
![View6](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/manage_icon.png)

- 사람 관리 페이지 위의 그룹 추가를 클릭
  
![View7](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/gsg_group_new.png)

- 제목 입력 후 그룹에 배정할 상담원을 선택 한 후 그룹 생성

</br>

### **고객 구성하기**

---

각 고객을 하나 이상의 조직에 추가할 수 있다. 사용자가 속하는 기본 조직은 고객이 만드는 모든 티켓과 연결되며 수신 티켓 처리 방식을 자동화하는 데 사용될 수 있다. 또한 조직에 상담원을 추가하여 상담원이 특정 조직의 티켓에만 액세스하도록 제한할 수 있다.

![View8](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/gsg_org_list_new.png)

사용자들을 특정 태그에 추가하고, 자동으로 티켓을 배정하거나 추적할 수 있다.
예를 들어 사용자나 조직에 프리미엄 태그를 추가하면 해당 조직 사용자들의 모든 티켓에 태그가 자동으로 추가되며, 태그를 사용하여 프리미엄 티켓을 추적하는 새 보기를 정의할 수 있다.

</br>

### **조직 만들기**

---

- 새 지원 티켓을 연다.
  
![View9](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_org.png)
  
- 3개의 탭(조직, 사용자, 티켓)
  
- 조직(만들기)을 클릭

![View10](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/gsg_new_org.png)

- 조직 이름을 입력
  
- 이메일 도메인이 같은 다른 모든 신규 사용자들을 자동으로 조직에 추가할 하나 이상의 이메일 도메인을 추가할 수 있다.

- 새 조직이 만들어져 티켓과 연결된 사용자의 프로필에 추가된다.

</br>

### **관리자**

---

관리자는 지원하려는 채널로 계정을 설정하고, 새 공유 보기를 정의하고, 사용자를 관리하는 등의 작업을 수행한다.

Zendesk의 계정을 만든 사람은 계정 소유자이며, 최고 관리자 역할로 한 명 또는 여러 명의 관리자를 지정할 수 있다.

![View11](https://zen-marketing-documentation.s3.amazonaws.com/docs/ko/gsg_user_roles.png)

</br>

### **상담원을 추가하여 그룹 및 조직에 배정하기**

---

![View12](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_user_add.png)

- Support에서 위쪽 도구 모음에 있는 추가 탭의 사용자를 클릭

- 새 상담원의 이름 및 이메일 주소 입력
  
- 사용자 역할을 상담원으로 선택한 다음 저장

- 그룹 필드를 클릭해 생성된 그룹에 배정

- 액세스 필드를 클릭해 상담원의 액세스 권한을 설정

- 특정 조직에만 액세스 제한을 두기위해 상담원을 특정 조직에 추가 (조직 필드 클릭 후 원하는 조직 선택)

</br>

### **2-3) [티켓 해결하기](https://support.zendesk.com/hc/ko/articles/4408882997530)**

</br>

### **고객에게 티켓 업데이트 알림**

---

![email](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/gsg_request_received.png)

티켓이 만들어지면 고객에게 이메일을 보내 티켓이 접수되었음을 알리는데, 이러한 이메일 알림은 티켓 유형이 업데이트된 후에 고객에게 자동으로 전송된다.

새 지원 요청을 받으면 사용자에게 이메일 알림을 통해 해당 요청을 받았음을 알리고, 필요한 경우 티켓의 링크를 알림에 포함하여 최종 사용자(고객)이 알림에 답장하여 티켓을 업데이트할 수도 있다.

각 이메일 답장은 티켓에 새 댓글로 추가되며, 이러한 이메일 알림의 기본서식을 수정하여 사용할 수 있다.

</br>

### **티켓 유형 및 우선 순위**

---

### 첫 번째 특성 **유형**

</br>

![case](https://zen-marketing-documentation.s3.amazonaws.com/docs/ko/gsg_type_select.png)

- 질문 : 요청자가 제기한 사항이 해결이 아닌 질문인 경우
  
- 문제 : 요청자가 제품이나 서비스상 문제를 제기하여 이를 해결해야하는 경우

- 사건 : 여러 사람에게 영향을 미치는 문제가 생겼을 때 사용되며, 사건 티켓은 문제 티켓에 연결되며 문제 티켓이 해결되면 해당 문제의 모든 사건이 동시에 자동으로 해결된다.

- 작업 : 특정 상담원에게 티켓을 작업 대상으로 배정하고 싶을 때 사용된다. 작업을 선택할 때에는 작업 기한도 설정해야 한다.

</br>

### **<문제 및 사건의 예>**

</br>

- 갑자기 아무도 사내 wiki에 접속하지 못하고 문서에도 액세스할 수 없다고 가정  

- 지원 요청이 쇄도

- 각 티켓을 개별적으로 처리하는 대신 문제를 요약한 티켓을 생성  

- 그런 다음 모든 개별 지원 요청을 이 문제 티켓에 연결  

- 문제가 해결되어 만든 문제 티켓을 해결로 표시 > 모든 사건 티켓 자동으로 해결

</br>

### 두 번째 특성 **우선 순위**

</br>

![priority](https://zen-marketing-documentation.s3.amazonaws.com/docs/ko/gsg_priority_select.png)

티켓 우선 순위는 각 티켓의 긴급도를 나타내며, 티켓을 관리하기 위해 Zendesk Support에 설정한 규칙에 사용될 수 있다.

우선 순위 값은 낮음, 보통, 높음, 긴급 4가지 값이 있으며, 티켓의 우선 순위는 본인이 정하면 된다.

예를 들어, 요청을 제출한 고객이나 티켓이 만들어진 후 경과한 시간에 따라 티켓을 긴급으로 배정할 수 있다.

</br>

### **반복되는 질문에 응답하기(매크로)**

표준 응답이 필요한 문제 또는 반복되는 질문에 대한 요청을 처리하기 위해 **매크로**를 사용한다.

매크로는 어느 티켓에든 쉽게 적용될 수 있는 미리 정의된 응답이고, 별도의 응답을 만들어 그러한 질문 각각에 상담원이 응답하는 대신 모든 상담원들이 사용할 수 있는 하나의 응답을 만들 수 있다.

![macro](https://zen-marketing-documentation.s3.amazonaws.com/docs/ko/support_intro_macro2.png)

- 전체 매크로 : 모든 상담원이 사용할 수 있다.

- 제한 매크로 : 특정 그룹의 상담원만 사용할 수 있다.

- 개인 매크로 : 생성한 상담원만이 사용할 수 있다.

</br>

### **자리 표시자로 매크로 개인화하기**

자동 응답을 보내는 것이 아니라 직접 대화하는 것처럼 고객이 느낄 수 있도록 하는것이 중요하다.  
매크로 및 고객에게 보내는 다른 알림을 사용할 때 고객별 데이터를 포함하도록 하는 **자리 표시자** 기능이 있다.

자리 표시자 : 고객에게 보내는 메시지에 추가할 수 있는 티켓 및 사용자 데이터에 대한 참조

<예시>

고객의 이름으로 매크로를 시작하려면 {{ticket.requester.first_name}} 자리 표시자를 추가한다. 그런 다음 매크로가 처리되고 티켓이 업데이트되면 고객이 "고객님께"라는 일반 인사말 대신 "안녕하세요, ???님"으로 시작하는 메시지를 받게 된다.

</br>

### **2-4) [셀프 서비스](https://support.zendesk.com/hc/ko/articles/4408885934234)**

</br>

### **헬프 센터**

---

고객이 스스로 문제를 해결할 수 있도록 돕는 방법

- [Guide](https://support.zendesk.com/hc/ko/articles/4408846795674) : 헬프 센터라는 브랜드별 고객 지원 사이트 (자주하는 질문 등)
- [Gather](https://support.zendesk.com/hc/ko/categories/4405303666330) : 최종 사용자(고객)들의 커뮤니티

- [추가로 실제 FAQ를 만드는 예시](https://blog.naver.com/st9dog/222721227701)

</br>

### **2-5) [비즈니스 규칙](https://support.zendesk.com/hc/ko/articles/4408885959066)**

</br>

### **자동화와 트리거**

---

티켓에 자동으로 적용되는 미리 정의된 작업으로, **자동화**와 **트리거**라는 두 가지 자동 비즈니스 규칙이 존재한다.

이 규칙을 만드는 목적은 상담원이 이러한 반복적인 작업을 더 이상 수동으로 하지 않도록 하기 위함이다.  

자동화와 트리거는 **관리자**만이 생성 및 관리를 할 수 있다.

</br>

### 공통점

---

### **if x is true, then do y**

티켓이 특정 **조건**에 일치할 때 실행되는 일련의 **작업**을 정의한다.  
자동화나 트리거에 포함된 **조건**을 충족하지 않으면 아무 일도 일어나지 않는다.

</br>

### 차이점

---

티켓을 수정하게 만드는 이벤트의 종류

- 자동화 : 이벤트 발생 후 경과 시간에 따라 티켓에 작업을 수행 (ex: 티켓이 업데이트되고 4시간 후)

- 트리거 : 티켓이 만들어지거나 업데이트될 때(만들기 및 업데이트 이벤트) 티켓에 작업을 수행한다.

</br>

### **조건**

---

티켓과 사용자 필드 및 그러한 필드에 포함된 데이터에 대한 참조

조건에는 **모두** 충족과 **하나** 이상 충족, 이렇게 2가지 종류가 있다.

![All condition](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_action3.png)

- 모두 충족 : 하나라도 맞지 않다면 실행하지 않는다.

![Any condition](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_action2.png)

- 하나 이상 충족 : 적어도 하나는 맞아야 실행한다.

작업과 달리 조건 문을 구축하는데 사용하는 연산자를 포함한다.  

</br>

### **작업**

---

조건이 맞아야 티켓에 실행되는 작업이다. 작업 문도 조건과 같은 형식을 따르지만 일치하는 여부를 테스트하는 것이 아니라 작업이 티켓 특성을 설정하고 이메일 알림을 보낸다.

![do](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_action1.png)

</br>

### **Zendesk에서 제공하는 알림 트리거**

---

Zendesk Support의 관리자 보기에서 트리거 페이지 선택  
( 관리자 아이콘 (![adminIcon](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/manage_icon.png)) 을 클릭 > 비즈니스 규칙 > 트리거 )

</br>

### **요청자에게 접수된 요청에 대해 알림** 트리거

해당 트리거는 신규 티켓을 접수할 때 티켓 요청자에게 이메일 메시지를 보낸다.

![ex_trigger](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_trigger1.png)
![ex_do](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/support_intro_trigger2.png)

- 티켓이 신규 생성이고, 상태가 해결되지 않았을 때에만 작업을 실행

- 작업들의 조합을 사용하여 이메일 알림을 생성

또한, **에스컬레이션**이 필요한 수신 티켓을 식별하기 위해 사용자 및 조직 프로필에 추가한 **태그**를 사용할 수 있다.

</br>

### **Zendesk에서 제공하는 자동화**

---

Zendesk Support의 관리자 보기에서 **자동화** 페이지를 선택  
(관리자 아이콘(![adminIcon](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/manage_icon.png)) > 비즈니스 규칙 > 자동화)

자동화는 이벤트 발생 후 경과 시간을 기준으로 하므로 특정 이벤트가 발생하고 지정한 시간이 지난 후 티켓 업데이트를 할 수 있는 추가 조건을 포함한다.

예를 들어, 티켓이 만들어진 후 지정한 시간이 지나면 티켓의 우선 순위를 **긴급**으로 설정하는 자동화를 만들 수 있다.

### **해결된 티켓을 4일 후 종료 상태로 변경**

티켓이 해결되고 4일 후 티켓을 종료하는 것이 기본으로 설정되어 있으나, 이 자동화를 변경하여 최대 28일까지 원하는 일 수를 설정할 수 있다.

</br>

### 자동화의 일반적인 사용 사례

---

- 배정된 티켓이 x시간 동안 미해결 상태인 경우 상담원에게 알리기
  
- 신규 티켓이 x시간 동안 미배정 상태인 경우 상담원 그룹에게 알리기

- 티켓이 터치되지 않고 특정 시간이 경과하는 경우 티켓의 우선 순위 높이기

- 보류 티켓이 요청자에 의해 업데이트된 지 x시간 후 배정된 상담원에게 알리기

- 티켓이 해결 상태로 설정된 지 x일 후 티켓 종료하기
