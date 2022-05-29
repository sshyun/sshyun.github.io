---
layout: post
current: post
cover: assets/images/20220522/presentation-cover.jpg
navigation: True
title: 발표는 어렵다
date: 2022-05-22 20:40:00
tags: work
class: post-template
subclass: 'post'
author: sshyun
---

# PT는 언제쯤 잘 할 수 있을까?

### PT는 어렵다.

리더가 되면서 상반기 한번, 하반기 한번 성과 발표 PT가 있다.
이번 상반기 발표는 5월이었는데. 상반기도 안 끝났는데 무슨 발표? 하는 사람도 있을 것이다.
6월에 맞춘 상위 보고를 하려면 우리는 5월에 정리해야 한다. 하반기는 11월에 준비해야 하고...하고..이맘때 쯤되면 머리가 아프고 속이 쓰리다. 개발자가 아니라 소설가가 처음 글 쓰는 데만 2~3주를 집중 해야 한다.
열심히 할 필요가 있나? 이 발표로 우리가 한 일을 정리하기도 하지만 다른 부서에 자랑하고, 팀원들을 으쓱하게 만들어야 하는 목표도 있다.
가장 어려운 것은 15분 안에 끝내야 한다는 것... ㅜㅜ;

15분 안에 수십 명의 청중에게 우리 팀이 한 일을 핵심만 추려서 알려줘야 한다.
발표도 후덜덜 어려운데 자료 만드는 건 거 힘들다.
지금까지 몸으로 익힌 노하우 몇 개를 잊지 않도록 정리해 본다.


### 핵심 포인트
오늘의 핵심포인트 이다. 바쁜 분들은 이것만 기억해라.

* **1. 앞에서 끝내야 한다.** 
* **2. 듣는 사람을 설득해라.** 
* **3. 스토리를 먼저 만들어라.**
* **4. 상대방의 입장에서 생각하라.**
* **5. 디자인 보다 내용이다.**


### 앞에서 끝내야 한다.

![](assets/images/20220522/pt_1.jpg)

#### 1.두괄식으로 정리해라.
**발표 도입부에서 이 발표를 끝내야 한다.**
처음 PT 만들 때 이 실수를 제일 많이 한다. 하는 일의 나열만 하다 보니 앞부분이 장황해지고, 앞에서 벌써 청중들은 지루해한다..

내가 작성한 초기 글의 흐름이다.
* 작년에 이어 올해는 시스템의 안정성을 위해 단단한 인프라 구축이 목표
* 이전의 시스템의 수정을 통해 효율화 진행
* 내년에는 이런 시스템을 가지고 서비스 경쟁력 향상을 가져가겠다.

처음에 이게 뭐가 잘못된 것인지 잘 이해가 안 되었다. 할 이야기를 썼고 성과는 이렇다고 정리했는데 뭐가 문제일까?
이 내용을 듣는 사람은 아래처럼 느낄 것이다.

> 무슨 이야기를 하려는 거지? <br/>
> 아... 그냥 저런 거 했구나... <br/>
> 지루하네...이 문장을 이렇게 바꿔보자.

* 올해 개발의 방향성 - 시스템 안정화
  * 단단한 인프라의 구축
  * 시스템 리팩토링을 통한 유지 보수 효율화
  * 내년 개발 목표 - XXX 시스템 개발로 서비스 경쟁력 강화

앞의 내용보다 목적과 의미가 제목에서 드러난다. 앞에서 주제를 먼저 정리 하고, 뒤에서 이를 설명하는 흐름이 되어야 한다.
PT의 모든 내용은 두괄식으로 정리해야 한다. 왜냐하면 대부분 청중은 PT에 집중하지 않는다. 앞에서 핵심 내용을 정리해 주면 뒤 내용을 듣지 않아도 이 발표의 핵심은 전달 한 셈이다.

 **2. 내용의 앞에서 이 발표의 주제를 한 문장으로 정리해서 보여 주어야 한다.**
말이 길면 의미 전달력이 떨어진다. 아래 내용을 보자.

* 사업 목적
 * 외부 데이터를 사용한 도구 개발
 * 서비스의 웹 사이트, 애플리케이션 제작 플랫폼 제공

일반적인 설명이다. 하지만 그게 전부이다. 어떤 시스템인지 설명은 하지만 목적도 희미하고 필요성도 느껴지지 않는다.

> 사용자가 API를 활용해 웹 사이트를 레고 블록처럼 만드는 No Code Platform입니다. <br/>
> 개발자는 낮은 비용으로 서비스에 추가할 수 있습니다.

어떤가? 한 문장으로 앞에서 이야기한 내용을 담으면서 함축적으로 특징을 이야기한다.
글이 길어지면 청중이 지루해한다. . 하지만, 너무 요약해도 독이 되는 경우가 있다.

*디자인 시스템 도입 -> UI 파편화 방지 및 공용 UI 개발*

짧아 보이지만 너무 줄여서 의미 이해가 쉽지 않다.

*디자인 시스템은 UI 파편화의 방지와 공용 UI 개발을 위해 도입 필요*

조금 길기는 하지만 더 정확하게 의미 전달이 가능하다.
핵심만 짧게 하지만 이해하기 쉽게... 말은 쉽지만, 막상 해보면 제일 어려운 과정이다.

### 듣는 사람을 어떻게 만들것인가?

![](assets/images/20220522/pt_2.jpg)

PT는 설득이다. 발표로 청중을 설득해야 한다. 발표가 끝난 후에 듣는 사람이 어떻게 될지 먼저 정의 해라.
이 발표를 하고 나면 듣는 사람은 의도한 상태나 상황이 되어야 한다.

> 이 제품을 꼭 쓰고 싶은데? <br/>
> 이 플랫폼은 기능이 좋구나.

이런 기대치를 먼저 정하고 내용을 써보자. 어떻게 설득해야 할지 조금 더 깊은 고민을 할 수 있다.

### 스토리를 먼저 만들어라.

![](assets/images/20220522/pt_3.jpg)

PT는 이야기이다. 발표가 무슨 소설이야고 하지만, 내가 배운 PT는 짧은 소설이다.
도입부 -> 중간과정 -> 결론
무엇을 이야기할지 스토리를 만들어야 한다.

듣는 사람이 신사업의 목표를 보고 우리에게 투자해야 한다고 해보자.

두서없는 순서의 예시이다.
* 신사업 목적 및 현황
 * 사업의 목적
 * 현재 현황
* 개발 전략 및 로드맵

당신은 이 사람에게 투자하겠는가? 비전도 약하고 설득도 안 된다.
그럼 어떻게 이 사람이 투가 하게 만들까?

다시 잡아본 이야기의 흐름은 이렇다.
* 우리 제품은 이거다.
* 최근 이쪽 시장 상황이 이렇다.
* 근데 지금 회사에는 이런 솔루션이 없다.
* 우리는 이미 만들고 있고, 우리가 회사 내 최고다
* 앞으로 이런 목표를 가지고 3년 뒤에는 이렇게 성장할 것이다.

상대방을 설득하게 하려면, 근거로 설득 해야 한다. 그것도 수치와 객관적인 자료면 더욱 좋다.
이런 종류의 문서를 피치 덱(pitch deck)이라고 한다.

> 피치 덱(pitch deck)은 5분에서 10분 정도의 짧은 시간의 발표 형식에 최적화되어 있는 투자제안서의 요약 버전입니다. <br/>
> 무엇보다 투자자가 투자가치 판단이 가능한 피치 덱이 핵심입니다. <br/>
> 투자가치 판단에 요구되는 설득력 있는 내용 구성과 스토리라인의 완결성이 중요합니다.

스타트업에서 주로 PT 할 때 사용하는 방식이다. 이런 PT를 위한 템플릿 솔루션도 있다. ([piktochart](https://piktochart.com/))
스타트업들은 이런 PT로 투자받아야 하니 나 같은 초보는 생각도 못 할 일이다.

### 상대방의 입장에서 생각하라.

![](assets/images/20220522/pt_4.jpg)

이번에 PT를 만들면서도, 제일 많이 지적받은 것이 내 할 말만 늘어놓는다는 라는 지적이었다.
PT를 적다 보면 어느샌가 내가 하고 싶은 이야기만 적고 있다.

> '나 이거 잘했고, 이런 거 했어요. 그래서 이런 거 할 거예요'

듣는 사람은 그걸 알고 싶은 게 아니다. 이런 게 궁금하지 않을까?

> 저 팀은 저렇게 문제를 풀었구나. <br/>
> 저 기능은 저래서 만들었군. <br/>
> 저런 경험도 했네! 나중에 물어봐야지.


듣는 사람이 궁금한 이야기를 해야 잘 들어준다. 이 발표를 통해서 어떤 걸 듣고 싶은지도 생각하면서 자료를 만들어야 한다.
내가 할 말만 하면 듣는 사람들은 시간만 낭비할 뿐이다.

### 논리적으로 이야기를 만들어라.

![](assets/images/20220522/pt_5.jpg)

이야기는 What,Why -> How -> Now 순으로 풀면 좋다.
이번에 큰 도움을 받은 내용이다. PT 내용이 산만하고 정리가 안 돼서 고민을 하는 중에 팀 동료가 조언을해주었다.

* 모듈화 개발
  * 기존 문제
  * 솔루션
  * 상반기 진행 상황
* 디자인 시스템
  * 기존 문제
  * 솔루션
  * 상반기 진행 상황

머리속에 딱 하고 박히는 방법이었다. 이런 문제를 이렇게 풀려고 했고 이만큼 했다. 이런 흐름이면 상대방이 이해하기 쉬운 논리구조가 될 것이다.
하반기는 이런 흐름이지 않을까? 

* 모듈화 개발
  * 문제
  * 솔루션
  * 올해 성과
* 디자인 시스템
  * 문제
  * 솔루션
  * 올해 성과

**이 일을 왜 했는지? 어디까지 했는지?** 가 내용의 핵심이었다. 이렇게 정리하고 나니 이전보다 내용 이해가 쉽고 의미 전달이 잘 되었다.

#### 디자인 보다 내용이다.

내가 못 버리는 습관이다. 다이어그램이나 그림에 너무 공을 들여서 정작 내용은 정리가 부실하다.
심지어 그림 때문에 내용이 집중되지 않는다는 의견도 들었다.
3시간을 그리면 뭐 하나 의미 없는 색 놀이인데

차라리 단순하게 의미를 드러내는 그림이 훨씬 좋다.

# 남들 앞에서는 아직...

![](assets/images/20220522/pt_6.jpg)

PT 만든 지는 한 3년 정도 돼가는 것 같다. 처음에는 만들어도 만들어도 늘지 않는 실력에 좌절하기도 했지만, 넘어지는 것도 훈련이라 이제는 다른 사람 것도 조금 볼 수 있는 상태가 되었다. 자료 작성에는 그나마 익숙해지고 있는데, 면대면으로 하는 PT는 아직도 낯설다.
스크립트를 다 외워서 능수능란하게 PT 할 수 있는 날이 올지 모르겠지만, 한 걸음 한 걸음 가다 보면 나아지겠지.
 