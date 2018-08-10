# HTML
- Hyper Text Markup Language

## [W3C](www.w3.org) (The World Wide Web Consortium)
- 국제민간표준화기구
- W3C에 소속된 여러 기업과 기관들의 논의를 통해 웹이 만들어짐
- 미래에 필요한 기능을 어떤 태그로 표현할지 의논 후 결정된 해당 태그를 각 브라우저 업체들이 보다 잘 구현하기 위해 경쟁함

## [W3school](https://www.w3schools.com/)
- 예제(Example) 먼저 보고, 정의(Definition)를 봐라

## [Advancedwebranking](https://www.advancedwebranking.com/html/)
- 구글에서 제공하는 웹페이지 분석 사이트
- `모든 언어는 태그별 인기도의 통계에 기반해 빈도수가 높은 태그부터 배워나가는 형태로 학습하면 효과적`

## 태그
### 한글문제
```
<meta charset="utf-8">
```
### 강조(굵게)
```
<strong></strong>
```
### 밑줄(underline)
```
<u></u>
```
### 닫지않는 태그
- 무엇인가를 설명하지 않는 태그들은 감싸야하는 컨텐츠가 없기때문에 태그를 닫지않음
```
<br />
<hr />
<img /> 
<input />
<meta />
...
```
- 단락(paragraph)
```
<p></p>
```
> p 태그는 단락과 단락의 간격이 고정되어있어 시각적으로 자유도가 떨어지나 br 태그는 쓰는만큼 줄바꿈이 되어 원하는 만큼 간격을 줄 수 있다. 하지만 css 를 이용해 이러한 p 태그의 한계를 극복할 수 있으므로 br 태그보다 p 태그가 더 좋다.

## 속성(attribute)
### img
- img 속성 : src(source)
```
<img src="주소">
```
> img 의 속성은 src 속성의 값은 주소
- `public domain (저작권없는)` image
- unsplash.com

## 부모(parent), 자식(child)
### 목록
#### ul, li
- unordered list : 순서(번호)가 없는 목록
- ul 은 다른 목록과 구분할 수 있도록 경계를 나눠줌

#### ol, li
- ordered list : 순서(번호)가 있는 목록

## 중요태그
```
<!doctype html>
<html>
<head>
  <title></title>
  <meta>
</head>
<body></body>
</html>
```
- title : 제목
- body : 본문
- head : 본문을 설명
- html : body와 head 태그를 감쌈
- !doctype html : 이 웹페이지는 HTML로 만들어졌다는 의미

## Anchor
- Hyper Text 를 의미하는 태그
- 링크
- a(anchor)의 링크속성은 href(Hypertext REFerence)
- title : 내용에대한 툴팁
- target : 페이지(새창, 현재창) 설정
