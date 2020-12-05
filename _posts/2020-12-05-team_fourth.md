---
layout: post
title: Issue 분석
date: 2020-12-05 20:31:28 +0300
img: 15.jpg
tags: Issue
---

PySnooper 프로젝트에 기여하기 위해 기존의 issue를 살펴보았다.

### 기존의 Issue

##### 1. 'relative_time' 버그
PySnooper를 제너레이터로 relative_time과 함께 사용하는 경우 실행 시간이 특정 시점에 리셋되는 문제가 있다.

##### 2. nesting 버그
PySnooper를 중첩해서 사용하는 경우 중첩된 PySnooper 이후의 코드는 출력이 되지 않는 버그가 있다.

##### 3. 특정 조건에서만 PySnooper 결과 출력
PySnooper를 사용할 때 'var>3'과 같은 조건을 인자로 전달해 이 조건을 만족하는 경우에만 PySnooper를 출력하도록 하는 기능을 추가하는 제안이 있다.

##### 4. 출력 시 구분을 위해 다른 색 사용
PySnooper을 사용한 결과를 출력할 때 한 가지 색으로 통일해서 출력되어 가독성이 어려운 문제점이 있다. 가독성을 높이기 위해 여러가지 색을 사용하는 것에 대한 요구가 있다.
