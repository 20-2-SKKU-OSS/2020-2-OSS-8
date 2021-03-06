---
layout: post
title: Team Project 개선방향
date: 2020-11-22 14:12:00 +0300
img: improvement_1.jpg
tags: 개선방향
---
앞서 선정 및 분석한 Pysnooper과 Tinykaboom 프로젝트에 대한 개선방안을 제시하고자 한다.

## Psynooper 프로젝트 개선방안
<ul>
      <li>호환성 부족 문제</li>
      <li>디버깅 기능 부족문제</li>
</ul>

<p><strong> 호환성 부족 문제 개선방안 </strong></p>
> 현재 가장 많은 코멘트가 달린 이슈를 보면 플랫폼에 따른 호환성 문제에 대한 것이다.
버전을 업그레이드함에 따라, 기존에 작동하던 플랫폼에서 오류를 일으키고 있는 것으로 보인다.
최근에는 python 3.8이 출시되어서 python 3.8버전이 추가되었고, 속도 개선, 다양한 버그 수정등이 있었다.
비록, 직접 해당 버그들을 완전히 해결하는 것은 쉬운 과제가 아니지만 “OSS 프로젝트 참여 경험”이 키워드인
본 실습수업의 목적을 고려해 보았을 때, 이러한 핵심적인 이슈에 대한 시도 및 노력 자체만으로도 충분히 의미 있는 작업이라고 판단된다.

<p><strong> 디버깅 기능 부족문제 개선방안 </strong></p>
> 소프트웨어 툴들이 디버깅 기능을 제공하고 있지만, 한눈에 보기가 쉽지 않고, 읽기 불편한 점 등의 기존의 고질적인 문제점들이 있다.
pysnooper는 코드를 포함하여 시간순으로 나열해서 보여주기에 상황파악과 읽기가 훨씬 쉬워진다.
디버깅 기능 개선을 통해 사용자에게 더욱 편리한 이용이 가능하도록 기존의 pysnooper 기능을 개선하고자 한다.
또한, 코드와 관련된 버그를 찾고 불필요할 때 디버깅 결과물이 출력되지 않고 특정 조건에서만 작동되도록 하는 개선방안이 필요하다.

## Tinykaboom 프로젝트 개선방안
<ul>
      <li>한정적인 출력 이미지</li>
      <li>번역 부족 및 복잡한 코드</li> 
</ul>

<p><strong>한정적인 출력 이미지 개선방안</strong></p> 
> 해당 Repository에는 gif, mp4, jpg형식의 파일들이 각각 존재하는데, 폭발하는 짧은 영상들도 포함되어있다.
하지만 실제로 프로그램을 실행시키면 ppm이라는 이미지 파일만 나오게 되는데, 여러 번 실행을 해도 같은 이미지만 나오게 된다.
이 부분을 다른 형식을 생성하게 하거나, 실행할 때마다 폭발하는 시점이 다른 랜덤한 이미지를 생성하면 사용자가 더욱 만족할만한
출력이미지를 얻을 수 있을 것으로 생각된다.

<p><strong>번역 부족 및 복잡한 코드 개선방안</strong></p>
> Wiki를 보면 폭발하는 이미지를 만들기 위한 과정이 상세하게 설명되어 있지만,
코드에는 설명히 잘 이루어져 있지 않아 오픈소스 프로젝트 개발자들이 코드를 분석하는데 어려움이 있다.
직접 폭발하는 이미지를 만드는 일련의 과정을 경험하면서 배우는 입장으로 처음 보는 사람도 이해하기 쉽도록 주석을 추가하는 것이다.
주석 입력과 함께 코드에 대한 최적화를 진행 할 경우 오픈소스 프로젝트 개발자들에게 편리함을 제공할 수 있을 것으로 보인다.
