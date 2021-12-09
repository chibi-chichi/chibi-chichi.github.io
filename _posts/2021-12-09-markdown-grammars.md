---
layout: post
title: 마크다운(Markdown) 문법 정리
tags:
  - markdown
  - summary
---

# Markdown이란?

[Markdown](https://whatismarkdown.com/)은 텍스트 기반의 마크업언어로 2004에 존 그루버에 의해 만들어졌다.
쉽게 사용하고 읽을 수 있으며 HTML로 변환이 가능하다는 것이 장점.
사용시에 특수기호나 문자등으로 간단하게 사용할 수 있어서 좋다.
이런 블로그 포스트에도 Markdown을 사용해서 쓰니 무슨 문법이 있는지 알아보자.

## Markdown 문법

## 헤더 Header

샵(#)을 앞에 붙힘으로써 큰 제목, 작은 제목, 글머리에 사용된다.

```
# 샵 하나만 사용할 때 제목
## 샵 2개를 사용할 때 소제목
### 글머리를 쓸 때 여러개 사용 가능하다
#### 샵 4개 사용
##### 샵 5개 사용
###### 하지만 샵 6개가 끝이다
```
예시)
# 샵 하나만 사용할 때 제목
## 샵 2개를 사용할 때 소제목
### 글머리를 쓸 때 여러개 사용 가능하다
#### 샵 4개 사용
##### 샵 5개 사용
###### 하지만 샵 6개가 끝이다
####### 샵 7개 이상을 사용했을 때는 텍스트로 나온다.


## 인용 블록 Blockquote

인용 블록은 흔히 말하는 인용구이며, ```>``` 기호를 사용해서 사용 가능하다.

```
> 인용구는 나O위키에서도 종종 볼 수 있다.
> > 인용구 안에 인용구를 쓸 수도 있다.
> > > ```어메이징하게도 인용구 안에 다른 Markdown 요소도 넣어서 사용할 수 있다.```
> > > > > > > > > > 10개까지 해봤는데 제한은 없는 듯 하다.
```

예시)

> 인용구는 나O위키에서도 종종 볼 수 있다.
> > 인용구 안에 인용구를 쓸 수도 있다.
> > > ```어메이징하게도 인용구 안에 다른 Markdown 요소도 넣어서 사용할 수 있다.```
> > > > > > > > > > 10개까지 해봤는데 제한은 없는 듯 하다.

## 목록 Lists

목록에는 2가지로 나뉘며 순서가 있는 목록과 순서가 없는 목록으로 나뉜다.

### 순서가 있는 목록 Ordered List

순서가 있는 목록은 흔히 사용하는 ```1. 2. 3.``` 등으로 나타낸다.

```
1. 첫 번째 목록
3. 번호를 이상하게 써도 순서는 무조건 내림차순으로 표시가 된다.
2. 두 번째 목록
4. 
5. 비어있어도 사용 가능하다.
```

예시)

1. 첫 번째 목록
3. 번호를 이상하게 써도 순서는 무조건 내림차순으로 표시가 된다.
2. 두 번째 목록
4. 
5. 비어있어도 사용 가능하다.

### 순서가 없는 목록 Unordered List

순서가 없는 목록은 3가지가 있다. ```*```, ```+```, ```-```로 사용이 가능하며 섞어서 사용하는 것이 가능하다.

```
* 색이 차 있는 동그라미
  + 색이 비어있는 동그라미
    - 네?모
    - 여러개 쓰는 것도 가능
      + 여러개 사용도 가능하다.
```

예시)

* 색이 차 있는 동그라미
  + 색이 비어있는 동그라미
    - 네?모
    - 여러개 쓰는 것도 가능
      + 여러개 사용도 가능하다.


`추가 요망`