---
layout: post
current: post
cover: assets/images/20220607/0607_cover.jpg
navigation: True
title: Article 서비스 오픈!
date: 2022-06-07 17:00:00
tags: work
class: post-template
subclass: 'post'
author: sshyun
---

# 드디어 Article 오픈

<figure>
  <img data-action="zoom" src='{{ assets/images/20220607/article_intro.png }}' alt='absolute'>
  <figcaption><a href="https://article.me" target="blank">Article Beta Service</a></figcaption>
</figure>

[https://article.me](https://article.me)



3년만에 오픈한 Article 서비스. 아직은 Closed Beta 서비스 이지만 3년만에 빛을 본 서비스이다.
( 참 우여 곡절이 많은 서비스이지만, 자세한 이야기는 대외비라..)

Article의 미션은,

> 현존하는 최고의 UGC 도구와 서비스의 개발

이였다. =ㅁ=;;
좀 과한 목표가 아닐까 싶었지만, 결과적으로는 이만한 도구와 서비스가 있을까 하는?

# 글쓰기 최강의 도구 SmartEditorONE

[SmartEditorONE 브랜드 사이트](https://smarteditor.naver.com/desktop/) (홈빌더도 만들어야지..)

SmartEditor를 아는 사람들은 많을것이다. (아마도 블로그 에디터로..)
하지만 의외로 스마트 에디터는 여러곳에서 사용된다.

- [네이버 스마트스토어의 상품글](https://shopping.naver.com/living/homeliving/stores/100641053/products/6767872476?NaPm=ct%3Dl43x3mj3%7Cci%3Dshoppingwindow%7Ctr%3Dswl%7Chk%3D1445408e54b3fdde61c60b96a855eae5a33cb8db%7Ctrx%3D)
- [네이버 프리미엄 콘덴츠의 편집기](https://contents.premium.naver.com/artandlife/knowledge/contents/220605213301550ra)
- [네이버 까페 글쓰기](https://cafe.naver.com/hkct/984714?art=aW50ZXJuYWwtY2FmZS1zZWN0aW9uLWVkaXRvcnMtcGljaw.eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJjYWZlVHlwZSI6IkNBRkVfSUQiLCJhcnRpY2xlSWQiOjk4NDcxNCwiaXNzdWVkQXQiOjE2NTQ1OTE3Nzg2MjEsImNhZmVJZCI6MTAxODYxMTl9.PAuYQWM_hu03YJC9yFzZHhRefyeDN9c6lp_r_jjSCs8)

SmartEditor는 다음 미션에 집중했다.

## 미려한 글쓰기

SmartEditor는 세련된 글을 빠르게 작성 가능한 에디터이다. 거기에 Mobile / PC / Tablet 까지 지원되는 글로벌에서도 찾아 보기 힘든 에디터라고 생각한다.
Article의 핵심 경쟁력은 글에서 나오는것이고 SE가 그 중심에 있다.

### Stylizer - SE만의 테마 시스템기술

<video class="AboutArticle__video__tY8_k" autoplay="" muted="" loop="" playsinline=""><source src="https://fe-article.pstatic.net/video/about_concept.61dd2a9081fb62af6a1b.mp4" type="video/mp4"></video>

원클릭으로 같은 글을 전혀 다른 UI로 표현 할 수 있다면?
SE의 문서는 HTML 이아닌 데이터로 되어있어 UI와 내용의 분리가 가능하다.
그래서 같은 글의 데이터를 전혀 다른 UI 셋으로 변경 가능하다. 이를 위해서는 고도의 마크업 기술과 FE기술이 접목 되어야 한다.
SE가 가지고 있는 강력한 기능 중의 하나.

 Article 의 최초 시연때 이기능을 보고 외국관계자 들이 극찬을 했다는 일화는 아직도 기억이 난다.

## 다양한 글기능 지원

문서가 데이터로 되어있어 문서를 기반한 다양한 기능 구현이 가능하다. 아티클의 언더라인을 대표적인 예시로 들 수 있다.
(예시 : [언더라인 예시](https://article.me/post/6298f3c3bcff9f53a901c75c?underlineSentenceId=629d9f6def23c17329b96845))
문단마다 데이터 영역이 나누어져 있어 블록선택으로 댓글등을 달고 리액션이 가능하다.
HTML로도 가능 하긴 하지만, 데이터로 만들어져있어 기능구현이 쉽게 가능했다.
컴포넌트 기반 글쓰기로 다양한 추가 컴포넌트로 인터렉티브한 기능의 구현이 가능 하다.

<figure>
  <img data-action="zoom" src='{{ ../assets/images/20220607/article_se.png }}' alt='absolute'>
  <figcaption>대화 / 만화뷰어 컴포넌트</figcaption>
</figure>


## 어디서나 글을 작성 - 멀티디바이스

데이터 기반의 문서는 다양한 디바이스간의 편집을 가능 하게 해준다. SE는 PC WEB / Mobile WEB / iOS APP / Android APP을 모두 지원한다.
PC 에서 작성한 글을 모바일에서 수정하고, 다시 태블릿에서 불러 올 수 있다. 작가는 어디서나 원하는 기기로 글을 작성 할 수 있고, 편집도 가능 하다.
다양한 디바이스의 완벽게 지원하는 글쓰기 도구는 글로벌에서도 찾기 어렵다. (심지어 나는 찾지 못했다.)

# 작가의 글을 더욱 빛나게 하는 Article HomeBuilder

SE가 글을 돋보이게 한다면, Article의 홈빌더는 글쓴이의 글을 미려한 Home으로 보여준다.
자신이 쓴 최신글이나 소식등을 알리는 나만의 개벗있는 홈으로 외부에 나를 알리는 용도로 사용된다.
우리는 이런 홈을 원클릭으로 쉽게 편집하고, 다양한 스타일링을 지원하는 도구를 구현 했다.
 
<figure>
  <img data-action="zoom" src='{{ ../assets/images/20220607/article_homebuilder.gif }}' alt='absolute'>
  <figcaption>Article HomeBuilder</figcaption>
</figure>

HomeBuilder는 다음의 기능에 포커스를 맞췄다.

## 초보자도 쉽게 -  단순한 편집

글관련 컴포넌트를 클릭으로 삽입하고 모양을 쉽게 바꾸도록 지원한다.
최신글 목록을 클릭만으로 추가하고, 원하는 모양의 Layout으로 변경이 가능하다.

<figure>
  <img data-action="zoom" src='{{ ../assets/images/20220607/article_home_view.png }}' alt='absolute'>
  <figcaption>컴포넌트의 view 타입적용</figcaption>
</figure>

## 원클릭으로 한번에 스타일링- 다양한 테마

HomeBuilder의 사이트 정보도 SE와 동일하게 데이터로 되어있다. SE의 DNA를 가진 테마를 홈빌더에도 그대로 적용하여 원클릭으로 다양한 스타일링이 가능하다.
거기에 컬러 베리에이션까지 지원한다.

<figure>
  <img data-action="zoom" src='{{ ../assets/images/20220607/article_home_theme.png }}' alt='absolute'>
  <figcaption>홈의 다양한 스타일링</figcaption>
</figure>


## 다양한 기기지원 - 반응형 사이트

HomeBuilder도 다양한 기기의 화면을 지원한다. 편집기는 아직 PC만 지원 하지만 조만간 Mobile도 지원 할 예정이다.
View의 경우에는 완벽한 반응형을 지원 한다.

<figure>
  <img data-action="zoom" src='{{ ../assets/images/20220607/article_home_res.png }}' alt='absolute'>
  <figcaption>반응형 대응</figcaption>
</figure>


# 그래서 Article은 최강의 UGC 도구일끼?

최강의 도구라는 것은 정의에따라 다르다. 어떤 사람은 이런 기능없이 심플한 글ㄱ쓰기가 좋은 사람도 있을 것이고, 글내용에 집중 할 수있는 에디터를 선호 할 수도 있다.
Article은 글과 디자인의 두마리 토까를 잡아보려는 시도이다. 그 중심에 SmmartEditor와 HomeBuilder가 최고의 도구를 제공 하고있다.
글로벌 최강의 도구 인지 물어본다면 내 기준에서는 SmmartEditor와 HomeBuilder가 결합된 도구는 최강의 도구 라고 자부한다.
앞으로도 SmmartEditor와 HomeBuilder는 계속 진화 할 것이다. Article 서비스가 통해 우리의 도구기술을 글로벌에 알리는 관문으로 성공 하길 기원한다.
