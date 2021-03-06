---
layout: post
title: 파이썬(Python) 문법 정리 1
tags:
  - python
  - summary
---

# 목차

## 들어가기 전에
 
파이썬은 다른 언어들에 비해 매우 쉽고 코딩을 모르는 사람들도 이해하기 쉬우며, 다양한 라이브러리를 통해 다양한 프로그램을 만들 수 있다는 것이 장점이다.
필자는 프로그래밍을 한 번도 접하지 못한 사람들에게 처음 프로그래밍을 배우기 위해 추천하고 있는데, 첫 프로그래밍 언어를 자바스크립트로 잡아서 그런지 흥미를 가지기 힘들었지만 파이썬을 배운 후에는 쉽게 다른 언어들도 도전할 수 있게 되었다.

## 자료형 - 숫자형

숫자형은 말 그대로 숫자를 나타내는 형태이다. 일상생활에 우리가 많이 쓰이는 정수, 실수뿐만 아니라, 8진법, 16진법까지도 표현이 가능하다.

| 숫자형  | 출력 예시 | 표현 예시 |
|:--------|:-------:|--------:|
| 정수    | 39, 0, -39 | a = 39, 0, 39   |
| 실수    | 0.39, -0.39, 3.14*10^10   | a = 0.39, -0.39, 3.14E10   |
| 8진법    | 141   | a = 0o141   |
| 16진법    | A283   | a = 0xA283   |

8진법과 16진법은 잘 사용하지 않으나, 만약을 대비해서 표에 넣었다.

### 정수형

정수형(interger)은 말 그대로 정수를 나타내는 수이다. 양의 정수, 음의 정수, 0까지 모두 출력이 가능하다.

``a = 39 ``
``a = 0 ``
``a = -39`` 

### 실수형
실수형(floating-point)는 소수점이 포함된 숫자이다.

``a = 0.39``
``a = -0.39``

#### 컴퓨터식 지수 표현 방식

``a = 3.14E10``
``a = 3.14e10``

### 사칙연산

사칙연산은 수학과 같이 ``+``, ``-``, ``*``, ``/``를 사용해서 수학 계산을 한다.

~~~
>>> a = 3
>>> b = 9
>>> a + b
12
>>> a - b
-6
>>> a * b
27
>>> a / b
0.333
~~~

#### 제곱
파이썬에서 제곱은 ``a**b``로 표현할 수 있다. a의 b제곱(a^b)의 의미이다.

~~~
>>> a = 3
>>> b = 2
>>> a ** b
9
~~~

#### 나머지 값
프로그래밍에서 ``%`` 라는 연산자는 나눗셈의 나머지를 알려주는 연산자이다. 아래 예시를 보면 쉽게 알 수 있을 것이다.

~~~
>>> 39 % 4
3
>>> 4 % 39
4
~~~

4에서 39를 나누면 몫은 0, 나머지 값은 4가 된다.

#### 몫 값

``/`` 연산자를 이용하면 나누기가 되는 것은 위에서도 보여줬다.
``//`` 연산자를 이용하면 나누기에서 몫만 출력이 된다.

~~~
>>> 39 / 4
9.75
>>> 39 // 4
9
~~~

나머지 값인 9.75에서 몫값인 9만 출력이 되었다는 것을 알 수 있다.