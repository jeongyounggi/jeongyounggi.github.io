---
layout: post
title: "Node.js 설치"
author: "Jeong.younggi@memory-inc.com"
---

# Node.js 설치

테스트글입니다.

Node.js 공식 사이트에 들어가면 메인 페이지에 각 PC OS 환경으로 LTS 버전과 현재 버전으로 다운로드 가능.

LTS = 안정적 버전, 현재 버전 = 최신 버전

최신버전을 쓰면 내부 코드가 바뀔 수도 있기 때문에 안정적 버전을 쓰는 게 좋다.

다운로드를 받고 설치는 next만 누르면 끝 ! 설치 패키지에서 자동으로 전역 처리를 하기 때문에 설치 완료 후 확인 방법은


{% highlight shell %}
node -v # Node.js 버전 체크. 결과는 v.6.11.2 설치한 버전에 따라 다른 숫자.
npm --version # npm 버전 체크 v.5.3.0 이하 동일
{% endhighlight %}


_The end_
