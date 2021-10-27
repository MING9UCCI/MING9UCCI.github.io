---
date: 2021-10-22 10:51:40
layout: post
title: 한글 가독성 테스트
subtitle: '인줄 알았으나 HTML공부'
description: >-
  HTML과 CSS는 프로그래밍 언어가 아닙니다.
image: >-
  https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559821647/theme6_qeeojf.jpg
optimized_image: >-
  https://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_380/v1559821647/theme6_qeeojf.jpg
category: blog
tags:
  - first post
  - blog
  - welcome
author: minwoo
paginate: true
---
나는 <a href="#">네이버</a>가 열리는지 href를 통해 실험도 해볼 예정이다. 놀랍게도 테스트 결과 열리지가 않는다. 다음은 줄 바꿈이다.
가나다라마바사
가나다
가가
이번엔 br을 이용해서 해보겠다.가나다라마바사<br>가나다<br>가가<br>놀랍게도 br을 사용하지 않고 Brackets에서 줄바꿈을 한 것은 적용되지않는다.

> 대충 멋있는 말을 적을 것같은 칸이다. Nullam id dolor id nibh ultricies vehicula ut id elit.

새로운 점은 **이것이다.** 별을 두개 쓰면 강조되는 효과가 있다. lorem ipsum...

## Inline HTML elements

또 놀라운 점이 있다 해시태그 두개를 쓰면 title이 되고 대괄호에 내용과 그 옆에 소괄호로 사이트를 쓰면 그쪽으로 넘어가진다. [Naver](https://naver.com).

* **To bold text**, use `<strong>`.
스트롱을 쓰거나 별 두개를 박으면 강조인가보다.
* *To italicize text*, use `<em>`.
em은 글씨를 눕히는 기능
* Abbreviations, like <abbr title="HyperText Markup Langage">HTML</abbr> should use `<abbr>`, with an optional `title` attribute for the full phrase.
abbr은 점선밑줄 그리고 그 안에 타이틀을 끼워넣으면 마우스를 올려놓았을 때 설명이 나온다.
* Citations, like <cite>&mdash; Thiago Rossener</cite>, should use `<cite>`.
Citation은 부가설명 그건 cite로 표현한다.
* <del>Deleted</del> text should use `<del>` and <ins>inserted</ins> text should use `<ins>`.
글씨에 줄 긋기는 del 밑줄은 ins이다.
* Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`.
sup은 수퍼스크립트를 표현하는 것이고 sub은 섭스크립트이다.

그리고 별 하나를 쓰면 동글뱅이 점으로 카테고리처럼 처리되는 것같다.

# 해시태그

## 갯수로

### 크기가

#### 정해지는거였나보다

위에서 말한 내용 정정하면 해시태그 두개가 title이 되는게 아니라 헤딩 처리였나봄.

--page-break--

## Code

Cum sociis natoque penatibus et magnis dis `code element` montes, nascetur ridiculus mus.

```js
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
```

Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.

## Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

* Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

## Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![placeholder](https://placehold.it/800x400 "Large example image") ![placeholder](https://placehold.it/400x200 "Medium example image") ![placeholder](https://placehold.it/200x200 "Small example image")

## Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.
